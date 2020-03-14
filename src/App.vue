<template>
  <div id="app">
    <Header></Header>
    <div id="content">
      <b-row>
        <b-col cols="9" style="position:relative; overflow-y:auto; height:610px">
          <ResultDisplay></ResultDisplay>
        </b-col>

        <b-col cols="3" id="functional">
          <b-row id="search">
            <SearchField></SearchField>
          </b-row>

          <hr class="my-3">

          <b-row id="filter">
            <FilterField></FilterField>
          </b-row>

        </b-col>
      </b-row>
    </div>


  </div>
</template>

<script>
    import FilterField from './components/FilterField.vue'
    import SearchField from './components/SearchField.vue'
    import Header from './components/Header.vue'
    import ResultDisplay from './components/ResultDisplay.vue'

export default {
  name: 'App',
  components: {
      Header,
      FilterField,
      SearchField,
      ResultDisplay
  }
}
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
    background-color: #FCFCFC;
  }
  
  #functional{
    background: #E3E1E1;
  }

  #search{
    height: 250px;
  }

  #filter{
    height: auto;
  }

  #content{
    padding:24px;
    padding-top: 10px;
  }

  /* width */
  ::-webkit-scrollbar {
    width: 10px;
  }
  /* Track */
  ::-webkit-scrollbar-track {
    background: #f1f1f1;
  }
  /* Handle */
  ::-webkit-scrollbar-thumb {
    background: #888;
  }
  /* Handle on hover */
  ::-webkit-scrollbar-thumb:hover {
    background: #555;
  }
</style>
