<template>
  <div>
    <h4 style="margin: 0; padding: 3% 0% 0% 3%">Featured</h4>
    <div style="margin: 3%">
      <q-card inline style="min-width: 300px; width: 30%; height: 210px;">
        <q-card-media style="float: left; padding: 10px">
          <img src="~assets/Kira.png">
        </q-card-media>
        <q-card-title style="padding: 0px; padding-top: 10px;">Kira</q-card-title>
        <q-card-main>
          <q-checkbox readonly v-model="check1" style="float: right"/>
          <p class="text-faded">It's How You Know What's in Your Contracts</p>
        </q-card-main>
        <q-card-separator/>
        <q-card-main>
          Kira is a powerful machine learning software that identifies, extracts,
          and analyzes text in your contracts and other documents.
        </q-card-main>
      </q-card>
      <q-card inline style="min-width: 300px; width: 30%; height: 210px; margin: 0% 1%">
        <q-card-media style="float: left; padding: 10px">
          <img src="~assets/Doxly.png">
        </q-card-media>
        <q-card-title style="padding: 0px; padding-top: 10px;">Doxly</q-card-title>
        <q-card-main>
          <q-checkbox readonly v-model="check1" style="float: right"/>
          <p class="text-faded">Secure Portal for End to End Transactions</p>
        </q-card-main>
        <q-card-separator/>
        <q-card-main>Manage the entire legal transaction process from diligence to closing.</q-card-main>
      </q-card>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AppList',
  data () {
    return {
      check1: false
    }
  }
}
</script>

<style>
</style>
