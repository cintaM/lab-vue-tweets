<template>
  <div className="tweet">
    <ProfileImage :image="user.image" />

    <div className="body">
      <div className="top">
        <span className="user">
          <User :user="user" />
        </span>
        <TimeStamp :timestamp="timestamp" />
      </div>
    </div>

    <Message :message="message" />

    <Actions />
  </div>
</template>
<script>
import ProfileImage from "./ProfileImage.vue";
import User from "./User.vue";
import TimeStamp from "./TimeStamp.vue";
import Message from "./Message.vue";
import Actions from "./Actions.vue";

export default {
  name: "Tweet",
  components: { ProfileImage, User, TimeStamp, Message, Actions },
  data() {},

  props: {
    user: { type: Object },
    timestamp: { type: String },
    message: { type: String },
  },
};
</script>


<style scoped>
a {
  color: #42b983;
}
</style>
