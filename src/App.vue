<template>
  <div class="app">
    <div class="header-container">
      <h1 class="title">Weather App</h1>
      <div class="position">
        <div class="searchbar">
          <input type="text" class="Input-form" placeholder="Enter a city">
        </div>
        <button class="btn">Search</button>
      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style lang="scss">
#app {
  body{
    background-color: #121212 !important;
  }
  .header{
    background-color: #212730;
    border-radius: 20px;
    color: #fff;
    text-align: center;
    font-family: arial, sans serif;
  }
}
.header-container{
    height: 25rem;
    padding: 1.25rem 5rem;
    .title{
      margin-bottom: 2.5rem;
    }
    .position{
      display: flex;
      justify-content: center;
      height: 25rem;
    }
    .searchbar{
      margin-left: 0.5rem;
      margin-right: 0.5rem;
      width: 25rem;
    }
    .searchbar input {
      box-sizing: border-box;
      width: 100%;
      padding: 0.5rem;
      border-radius: 5px;
      border: 1px solid black;
    }
    .btn{
      height: 2rem;
      background-color: #0000FF;
      border-radius: 5px;
      border: none;
      padding: 0.5rem;
      color: white;
    }
  }

</style>
