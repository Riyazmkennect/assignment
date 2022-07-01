<template>
  <div >
     <!-- <Toggle :mode="mode" @toggle="$emit('toggle')" /> -->
     <Pod/>
 

  </div>
</template>

<script>
import status from '~/components/status.vue'
import Toggle from '~/components/Toggle.vue'
import Pod from '~/components/Pod.vue'
export default {
 components:{
    Toggle,
    Pod
 }
}
</script>

<style>

</style>