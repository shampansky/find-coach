<template>
  <section>
    <base-card>
      <h2>Register as a coach now</h2>
      <coaches-form></coaches-form>
    </base-card>
  </section>
</template>

<script>
import CoachesForm from '../../components/coaches/CoachesForm.vue';

export default {
  components: {
    CoachesForm,
  }
}
</script>