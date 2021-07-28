<template>
  <div class="rounded-lg shadow-md p-4 m-6 bg-white border-b-4 border-green-500">
      <h2>Name</h2>
      <h2>ID</h2>
      <h3>Teacher</h3>
  </div>
</template>

<script>
export default {
    props:{
        name : { default : "Unknow name" },
        id : { default : "Unknow id" },
        teacher : { default : "Unknow teacher" },

    }

}
</script>

<style>

</style>