<template>
  <div class="home">
    <Nav></Nav>
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
</template>

<script>
// @ is an alias to /src

import Nav from '@/components/Nav'
export default {
  name: 'Home',
  components: {
    Nav
  }
}
</script>
