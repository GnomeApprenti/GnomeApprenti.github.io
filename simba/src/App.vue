<script>
import NavLink from './components/NavLink'

export default {
  name : 'App',
  components: {
    NavLink
  }
}
</script>

<template>
  <div id='app'>
    <nav>
      <NavLink url="/" text="Accueil"/>
    </nav>
  </div>
</template>