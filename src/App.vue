<template>
  <h1>{{ title }}</h1>
  <counter />
</template>

<script>
import Counter from './components/Counter'

export default {
  name: 'App',
  data: () => ({
    title: 'Counters'
  }),
  components: { Counter }
}
</script>
