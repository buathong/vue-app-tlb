<template>
  <div>
    <nuxt-link to="/tabled"><center>Buathong->click.</center></nuxt-link><br>
    <router-link :to="{ path: '/student1'}" replace><center>Register</center></router-link><br>
    <router-link :to="{ path: '/student1'}" push><center>Register</center></router-link><br>
  </div>
</template>
<script>
export default {
  data() {
    return {
      id: 1,
    }
  },
}
</script>
