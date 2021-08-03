<template>
<div >
  <p> {{greeting}} World </p>
  <button v-on:click="count++">You clicked me {{ count }} times.</button>
</div>
<br>
</template>

<script>
export default {
  data () {
    return{
      greeting: 'hello',
      count: 0,
     
    }
  }
}  
</script>