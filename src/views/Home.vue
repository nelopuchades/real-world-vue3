<template>
  <div class="home">
    <event-card />
  </div>
</template>

<script>
// @ is an alias to /src
import EventCard from '@/components/EventCard.vue'

export default {
  name: 'Home',
  components: {
    EventCard, // register it as a child component
  },
}
</script>
