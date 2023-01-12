<template>
  <b-container>
    Willkommen bei RegioSports

    <sportart-list />

  </b-container>
</template>
<script>
import SportartList from "@/components/sportart/SportartList.vue"
export default {
  name: "HomeView",
  components: {SportartList }
}
</script>

