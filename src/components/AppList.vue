<template>
  <div>
    <h4 style="margin: 0; padding: 3%">Featured</h4>
    <q-card inline style="min-width: 300px; width: 30%; margin: 0% 3%">
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
