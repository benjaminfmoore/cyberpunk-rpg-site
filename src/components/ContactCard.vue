<template>
  <div class="profile-card">
    <img :src="Jay" alt="Contact Card" />
    <p>Roll!</p>
  </div>
</template>

<script>
import Jay from "@/assets/J.png";

export default {
  name: "ContactCard",
  data() {
    return {
      Jay: Jay,
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
