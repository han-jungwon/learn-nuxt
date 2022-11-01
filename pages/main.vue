<template>
  <div>
    <h1>메인페이</h1>
  </div>
</template>
<script>
import axios from 'axios'
export  default {
  async created() {
    const response = await axios.get('https://localhost3000/products')
    console.log(response)
  }
}


</script>
