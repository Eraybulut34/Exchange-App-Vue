<template>
<b-row>
  <b-col v-for="new1 in news" :key="new1">
    <div class="news">
      <b-card
        :title="new1.title"
        :img-src="new1.urlToImage"
      >
        <b-card-text>
          {{ new1.description }}
        </b-card-text>

        <b-button :href="new1.url" variant="primary">Haberi Gör</b-button>
      </b-card>
    </div>
  </b-col>
  </b-row>
</template>

<script>
export default {
    data() {
    return {
      news: null,
    }
  },
  methods: {
  },
}
</script>

<style scoped>

</style>