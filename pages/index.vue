<template>
  <Tutorial :meta-tag-details="metaTagDetails" />
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      metaTagDetails: {
        title: 'Tutorial',
        description: 'This page is tutorial page.',
      },
    }
  },
}
</script>
