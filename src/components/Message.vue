<template>
  <div>
    <h1>I'm part of the Message component!</h1>
    <slot>
      <h2>I'm a default heading that appears <em>only</em> when no slots have been passed into this component</h2>
    </slot>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
