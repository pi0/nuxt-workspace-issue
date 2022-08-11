<template>
  <div>
    Nuxt app! {{ id }}
  </div>
</template>

<script lang="ts" setup>
import {v4} from "uuid"

const id = v4()
</script>
