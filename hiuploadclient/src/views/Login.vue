<template>
  <div class="home">
    <form action="" @submit.prevent="login">
      <button type="submit">login</button>
    </form>
  </div>
</template>

<script>
import {mapActions} from 'vuex';

export default {
  name: 'login',
  components: {
  },
  methods:{
    ...mapActions({
      loginAction:'auth/login'
    }),
    login(){
       this.loginAction({email:"ahmed-habeeb@outlook.com",password:'password'})
    }
  }
}
</script>
