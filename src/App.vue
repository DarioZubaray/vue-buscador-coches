<template>
  <div id="app">
    <div class="container my-3">
      <vuex-search-form></vuex-search-form>
      <vuex-search-list></vuex-search-list>
    </div>
  </div>
</template>

<script>
import VuexSearchList from './components/VuexSearchList'
import VuexSearchForm from './components/VuexSearchForm'
export default {
  name: 'app',
  components: {
    VuexSearchList, VuexSearchForm
  }
}
</script>
