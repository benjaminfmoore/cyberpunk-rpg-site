<template>
  <div class="about">
    <ServicesCardComponent />
  </div>
</template>

<script>
import ServicesCardComponent from "@/components/ServicesCard.vue";

export default {
  name: "ProfileCard",
  components: {
    ServicesCardComponent,
  },
};
</script>
