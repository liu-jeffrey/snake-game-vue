<template>
    <div class="cell" :style="style">
        <div class="food" />
    </div>
</template>

<script>
export default {
  props: {
    size: { type: String, default: "20px" },
    colour: { type: String, default: "white" }
  },
  data: function() {
    return {
      style: {
        width: this.size,
        height: this.size,
        backgroundColor: this.colour
      }
    };
  }
};
</script>

<style lang="scss" scoped>
.cell {
  border: solid 1px darkgrey;
}
</style>
