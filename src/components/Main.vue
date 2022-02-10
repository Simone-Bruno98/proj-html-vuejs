<template>
  <div class="hello">
    <AvailableServices/>
    <LearnMore/>
    <Sponsors/>

    </div>
</template>

<script>
import AvailableServices from './Macro/AvailableServices.vue'
import Sponsors from './Macro/Sponsors.vue'
import LearnMore from './Macro/LearnMore.vue'

export default {
  name: 'Main',
  components: {
    AvailableServices,
    Sponsors,
    LearnMore,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .hello{
  }
</style>
