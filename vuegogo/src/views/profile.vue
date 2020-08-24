<template>
  <div class="profile">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="media text-left">
            <img class="mr-3 user-pict" src="../assets/kiva.jpg" alt="Logo">
            <div class="media-body">
              <h5 class="mt-0">{{ firstname }} {{ lastname }}</h5>
              <p>Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  // @ is an alias to /src
  import 'bootstrap/dist/css/bootstrap.css'

  export default {
    name: 'profile',
    data: function(){
      return {
        firstname : 'Harun',
        lastname : 'Ar - Rasyid'
      }
    },
    component:{}
  }
</script>

<style scoped>
.user-pict {
  border-radius: 200%;
  height: 80px;
  width: 80px;
}
</style>
