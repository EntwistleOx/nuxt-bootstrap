<template>
  <div>
    <b-card-group columns class="mt-3">
      <b-card
        v-for="character in characters"
        :key="character.id"
        :title="character.name"
        :img-src="character.imgUrl"
        img-alt="Image"
        img-top
      >
      </b-card>
    </b-card-group>
  </div>
</template>

<script>
import { characters } from '../data/index'

export default {
  data: () => ({
    characters,
  }),
}
</script>
