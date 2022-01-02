<template>
  <div id="App">
    <p>{{myname}}</p>
    <Details>
      <template v-slot:ap>
        <p>apple</p>
      </template>
      <template v-slot:ba>
        <p>banana</p>
      </template>
    </Details>
  </div>
</template>

<script>
import Details from './components/Details.vue';
export default {
  name: 'App',
  components: {
    Details
  },
  data(){
    return{
      myname: 'akib'
    }
  }
}
</script>

<style>

</style>