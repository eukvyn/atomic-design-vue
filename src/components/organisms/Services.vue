<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste eum explicabo quaerat fuga reiciendis officia pariatur dolores, libero quam numquam odit. Reprehenderit in voluptate excepturi, tempora officia beatae quae veritatis!"
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste eum explicabo quaerat fuga reiciendis officia pariatur dolores, libero quam numquam odit. Reprehenderit in voluptate excepturi, tempora officia beatae quae veritatis!"
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste eum explicabo quaerat fuga reiciendis officia pariatur dolores, libero quam numquam odit. Reprehenderit in voluptate excepturi, tempora officia beatae quae veritatis!"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({ components: { Service } })
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
