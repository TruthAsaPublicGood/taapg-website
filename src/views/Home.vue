<template>
  <v-container fluid fill-height>
    <div class="hop-waves">
      <truth-public></truth-public>
      <Taapg-learn></Taapg-learn>
      <!-- <Taapg-toolkits></Taapg-toolkits>
      <Taapg-usecases></Taapg-usecases> -->
    </div>
  </v-container>
</template>

<script>
import TruthPublic from '@/components/TruthPublic'
import TaapgLearn from '@/components/TaapgLearn'
// import TaapgToolkits from '@/components/TaapgToolkits'
// import TaapgUsecases from '@/components/TaapgUsecases'

export default {
  name: 'Taapg-Content',
  components: {
    TruthPublic,
    TaapgLearn
    // TaapgToolkits,
    // TaapgUsecases
  }
}
</script>

<style>
.hop-waves {
  background-color: 'purple lighten-5';
  background-position: center center;
  background-repeat: repeat-y;
  width: 100%;
  height: 100%;
}
</style>
