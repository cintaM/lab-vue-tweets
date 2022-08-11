<template>
  <div className="actions">
        <i class="far fa-comment"></i>
        <i class="fas fa-retweet"></i>
        <i class="far fa-heart"></i>
        <i class="fas fa-share"></i> 
      </div>
      <div>
      <i class="fas fa-ellipsis-h"></i>
      </div>
</template>

<script>
export default {
  name: "Actions",
  props: {
   actions: String,
  },

}
</script>

<style>

</style>