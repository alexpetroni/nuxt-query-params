<template>
  <div>
    <h1>ID: {{ id }} query: {{ query }}</h1>

  </div>
</template>

<script>
export default {
  asyncData ({params, query}) {
    return {
      id: params.id, 
      query: query,
    }
  }
}
</script>
