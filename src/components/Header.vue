<template>
  <div>
    <div class="header">
      <a class="logo">Fly<span>Ops</span></a>
      <ul class="nav-link">
        <a class="link">Community</a>
        <a class="link">Online Classes</a>
        <a class="link">Application</a>
        <a class="link">Affliate Programs</a>
      </ul>
      <div class="right">
        <a class="link login">Login</a>
        <ButtonVue/>
      </div>
    </div>
  </div>
</template>
<script>
import ButtonVue from '@/components/Button.vue'
export default {
  components: {
    ButtonVue
  }
}
</script>
<style >

.header {
  display: flex;
  flex-direction: row;
  /* width: 100%; */
  padding: 1rem 4rem;
  align-items: center;
  justify-content: space-between;
  max-height: 20vh;
}
.logo {
  font-size: 1.4rem;
}
.logo span {
  color: orange;
}
li {
  list-style: none;
}
.nav-link {
  display: flex;
  flex-direction: row;
  align-items: center;
  /* margin-left: 2rem; */
}
.link {
  font-size: 1rem;
  margin: 1rem;
  cursor: pointer;
}
.right {
  display: flex;
  flex-direction: row;
}
.login {
  margin-right: 1rem;
}
.link:hover{
    opacity: 0.6;
  }
</style>
