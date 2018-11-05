<template>
  <div class="grid">
    <div class="row" v-for="n in size" :key="n">
      <cell v-for="m in size" :key="m"/>
    </div>
  </div>
</template>

<script>
import Cell from "./Cell.vue";

export default {
  data: function() {
    return {
      size: 30,
      snake: { direction: "right", length: 3 }
    };
  },
  mounted: function() {
    // while (true) {
    //   break;
    // }
  },
  components: { Cell }
};
</script>

<style lang="scss" scoped>
.grid {
  border: solid 1px darkgrey;
}

.row {
  display: flex;
}
</style>
