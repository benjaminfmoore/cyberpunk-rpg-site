<template>
  <div class="profile-card">
    <img :src="Ge" alt="Profile Card" />
    <p>Roll!</p>
  </div>
</template>

<script>
import Ge from "@/assets/G.png";

export default {
  name: "ProfileCard",
  data() {
    return {
      Ge: Ge,
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
