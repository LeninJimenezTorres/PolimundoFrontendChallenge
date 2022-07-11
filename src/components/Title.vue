<template>
    <div id="titulo">
        <h1>{{ msg }}</h1>
        <h2>{{subtitle}}</h2>
    </div>
</template>

<script>
export default {
  name: 'TitleComponent',
  props: {
    msg: String,
    subtitle: String,
  }
}
</script>

<style scoped>
    h1 {
        font-size: 2em;
        color: white;
        justify-self: center;
        align-items: center;
    }
    h2 {
        font-size: 1.2em;
        color: white;
        justify-content: center;
        align-items: center;
    }
</style>