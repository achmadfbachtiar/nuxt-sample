<template>
  <div class="container">
    <div>
      <h1>
        SAMPLE
      </h1>
      <sample-form :isEdit="false" />
      <button @click="back">
        back
      </button>
    </div>
  </div>
</template>

<script>
import {mapState} from 'vuex'
import SampleForm from '../ignore/SampleForm.vue'

export default {
  components: {
    SampleForm
  },
  computed: {
  },
  data() {
    return {
    }
  },
  fetch() {
  },
  mounted() {
  },
  methods: {
    back() {
      this.$router.go(-1)
    }
  },
  watch: {
  },
  filters: {
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
