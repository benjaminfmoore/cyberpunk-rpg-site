<template>
  <div class="profile-card">
    <img :src="El" alt="Profile Card" />
    <p>Roll!</p>
  </div>
</template>

<script>
import El from "@/assets/L.png";

export default {
  name: "ProfileCard",
  data() {
    return {
      El: El,
    };
  },
};
</script>

<style scoped>
.profile-card {
  text-align: center;
}

.profile-card img {
  max-width: 100%;
}

.profile-card p {
  margin-top: 10px;
}
</style>
