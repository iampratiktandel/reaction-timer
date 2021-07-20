<template>
  <p> Reaction Time : {{score}} ms </p>
  <p> Rank: {{rank}} </p>
</template>

<script>
  export default {
    props: ['score', 'rank']
  }
</script>