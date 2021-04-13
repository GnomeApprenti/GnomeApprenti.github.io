<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Hooks msg="Composant pour tester les hooks (voir console)"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Hooks from '@/components/Hooks.vue'

export default {
  name: 'Home',
  components: {
    Hooks
  }
}
</script>
