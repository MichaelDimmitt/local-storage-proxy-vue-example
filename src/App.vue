<template>
  <div id="app">
    network request, afterwich local storage; requests will occur below:
    <br/><br/>https://api.github.com/users/michaeldimmitt/repos
  </div>
</template>

<script>
// import proxy from "../proxy";
export default {
  name: 'app',
  components: {
  },
  data(){
    return {
      information: {}
    };
  },
  beforeMount() {
    // proxy.networkRequest(fetch('https://httpbin.org'))
    // .then(response => { return response.text(); })
    // .then(response => {
    //   this.information = response.data;
    //   return response.data;
    // })
    // .catch(error => { console.log('Get', 'fetch', {error}) })
    // .finally(() => {
    //   this.loading = false;
    // });
  }
}
</script>

<style>
</style>
