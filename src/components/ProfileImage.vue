<template>
    <img
      :src="image"
      className="profile"
    /> 
</template>

<script>
export default {
name: "ProfileImage",
  props: {
    image: String,
  },
}
</script>

<style>

</style>