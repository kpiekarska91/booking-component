<template>
  <main>
    <booking
      price="298"
      rating="4.5"
      numberOfVotes="123"
      :unavailableDates="[]"
      :selectedDates="[]">

    </booking>
  </main>
</template>

<script>


import Booking from './../components/Booking.vue'

export default {
  name: 'ViewHome',

  components: {
    Booking
  },

}
</script>
<style scoped>

</style>
