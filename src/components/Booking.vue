<template>
<div class="booking">
  {{price}}
  {{rating}}
  {{numberOfVotes}}
  {{unavailableDates}}
  {{selectedDates}}
</div>
</template>

<script>
export default {
  name: 'Booking',
  props: {
    price: {
      type: Number,
      required: true
    },
    rating: {
      type: Number,
      required: true
    },
    numberOfVotes: {
      type: Number,
      required: true
    },
    unavailableDates: {
      type: Array,
      required: false,
      default: () => []
    },
    selectedDates: {
      type: Array,
      required: false,
      default: () => []
    }

  }
}
</script>

<style scoped>

</style>
