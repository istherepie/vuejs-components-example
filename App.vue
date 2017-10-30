<template>
  <div>
    <h5>{{ message }}</h5>
    <p>{{ submessage }}</p>
  </div>

</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      message: 'Hello Frank',
      submessage: 'This is a submessage'
    }   
  },
  methods: {
    writeToConsole() {
      console.log('Writing something in the log')
    }
  },
  created() {
    this.writeToConsole()
  }
}
</script>
