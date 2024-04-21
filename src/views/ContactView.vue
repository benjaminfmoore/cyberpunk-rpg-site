<template>
  <div class="about">
    <ContactCardComponent />
  </div>
</template>

<script>
import ContactCardComponent from "@/components/ContactCard.vue";

export default {
  name: "ProfileCard",
  components: {
    ContactCardComponent,
  },
};
</script>
