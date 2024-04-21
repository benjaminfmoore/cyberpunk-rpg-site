<template>
  <div class="profile-card">
    <img src="@/assets/Elspeth.png" />
    <p>Roll!</p>
  </div>
</template>

<script>
export default {
  name: "ProfileCard",
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
