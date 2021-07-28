<template>
    <header>
        <h1>{{title}}</h1>
        <!-- <p>anything you can change</p> -->
    </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
      title: {
          type: String,
          default: 'Hello Abdul',
      },
  },
}
</script>


<style scoped>
h1 {
  margin: 40px 0 0 ;
  font-family: "Times New Roman", Times, serif;
}
</style>
