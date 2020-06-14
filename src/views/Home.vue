<template>
    <div>
      <Buttons />
      <Accordions />
      <Alerts />
      <Cards />
      <Checkboxes />
      <Inputs />
    </div>
</template>

<script>
// @ is an alias to /src
import Buttons from '../components/Buttons.vue'
import Accordions from '../components/Accordions.vue'
import Alerts from '../components/Alerts.vue'
import Cards from '../components/Cards.vue'
import Checkboxes from '../components/Checkboxes.vue'
import Inputs from '../components/Inputs.vue'


export default {
  name: 'Home',
  components: {
    Buttons,
    Accordions,
    Alerts,
    Cards,
    Checkboxes,
    Inputs
  }
}
</script>

<style>

h1 {
  font-family: Montserrat;
}

.container {
  display: flex;
  justify-content: space-around;
  width: 80%;
  margin: 0 auto 2em;
  border-radius: 10px;
  box-shadow: 0px 1px 3px 3px #DDD;
  padding: 2em;
  font-family: Montserrat;
}

</style>