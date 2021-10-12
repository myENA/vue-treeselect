<template>
  <treeselect
    :options="options"
    :multiple="true"
    :search-split-words="false"
    :flatten-search-results="false"
    placeholder="Where are you from?"
    />
</template>

<script>
  import countries from './data/countries-of-the-world'

  export default {
    data: () => ({
      options: countries,
    }),
  }
</script>
