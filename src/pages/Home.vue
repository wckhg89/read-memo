<template>
  <div>
    {{ user }}
  </div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  computed: {
    ...mapState('auth', ['user'])
  }
}
</script>
