<template>
  <form class="w-full space-y-5" ref="form" @submit.prevent="sendEmail">
    <input type="text" placeholder="Name" class="focus:outline-none w-full p-4 border rounded-xl bg-transparent border-zinc-600" name="user_name">
    <input type="email" placeholder="Email" class="focus:outline-none w-full p-4 border rounded-xl bg-transparent border-zinc-600" name="user_email">
    <input type="text" placeholder="Phone" class="focus:outline-none w-full p-4 border rounded-xl bg-transparent border-zinc-600" name="phone">
    <button :disabled="disable" class="bg-amber-400 text-zinc-800 px-8 py-3 rounded-xl" type="submit">{{ msgSent ? 'Message Sent Successfully' : 'Get help now' }}</button>
  </form>

</template>

<script>
  import emailjs from '@emailjs/browser';

  export default {
    data(){
      return{
        msgSent : false,
        disable : false
      }
    },
    methods: {
      sendEmail(){
        emailjs.sendForm('service_v7974ad', 'template_22miz6a', this.$refs.form, 'Q5u8EARMZt8TazyVU')
          .then((result) => {
            this.msgSent = true
          }, (error) => {
              console.log('FAILED...', error.text);
          });
        
      }
    }
  }
</script>

<style>

</style>