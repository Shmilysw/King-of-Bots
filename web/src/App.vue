<template>
  <NavBar/>
  <router-view></router-view>

</template>


<script>
import NavBar from './components/NavBar.vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap"

export default {
  components: {
    NavBar
  },
  setup() {
    // $.ajax({
    //     url: "http://127.0.0.1:3000/user/account/token/",
    //     type: "post",
    //     data: {
    //         username: "bb",
    //         password: "pbb",
    //     },
    //     success(resp) {
    //         console.log(resp);
    //     },
    //     error(resp) {
    //         console.log(resp);
    //     }
    // });

    // $.ajax({
    //     url: "http://127.0.0.1:3000/user/account/info/",
    //     type: "get",
    //     headers: {
    //         Authorization: "Bearer " + "eyJhbGciOiJIUzI1NiJ9.eyJqdGkiOiIyM2E2YWI3ZjZkZDM0Nzg3OTY5NTRiZDQxNzMzNzNlZCIsInN1YiI6IjIiLCJpc3MiOiJzZyIsImlhdCI6MTY2NDU5MzU0MiwiZXhwIjoxNjY1ODAzMTQyfQ.B8Gk7xzuEULkbQwz-ZtEL-_PQy3wJCO5Ss0nB309RDQ"
    //     },
    //     success(resp) {
    //         console.log(resp);
    //     },
    //     error(resp) {
    //         console.log(resp);
    //     }
    // });

    // $.ajax({
    //     url: "http://127.0.0.1:3000/user/account/register/",
    //     type: "post",
    //     data: {
    //         username: "sw2",
    //         password: "123",
    //         confirmedPassword: "123",
    //     },
    //     success(resp) {
    //         console.log(resp);
    //     },
    //     error(resp) {
    //         console.log(resp);
    //     }
    // })
  }
}
</script>

<style>
body {
  background-image: url("~@/assets/images/background.png");
  background-size: cover;
}
</style>
