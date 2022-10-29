<template>
  
</template>

<script>
import { defineComponent, useMeta, useContext } from '@nuxtjs/composition-api'

export default defineComponent({
  head: {},
  setup(_props, context) {
    const { $config } = useContext()
    useMeta({ title: `History - ${$config.siteTitle}` })
  },
})
</script>
