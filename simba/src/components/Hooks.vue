<template>
  <h1>{{msg}}</h1>
</template>

<script>

export default{
  name: 'Hooks',
  props: {
    msg: String
  },
  beforeCreate() { console.log('Je ne suis pas encore  créé') },
  created() { console.log('Je suis créé !') },
  beforeMount() { console.log('Je vais bientôt être monté sur le DOM!') },
  mounted() { console.log('Je suis monté sur le DOM!') },
  beforeDestroy() { console.log('Je suis sur le point de disparaître du DOM !') },
  destroyed() { console.log('Je suis supprimé') }
}
</script>
