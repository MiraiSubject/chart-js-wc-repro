<template>
  <div id="app">
    <div class="orange row">
      <div class="chartbg">
        <Chart />
      </div>
    </div>
  </div>
</template>

<script>
import Chart from "./assets/chart";
export default {
  components: {
    Chart,
  },
};
</script>
<style scoped>
.row {
  display: flex;
  flex-direction: row;
}

.orange {
  background-color: #f4e8d5;
  width: 100%;
  height: auto;
  padding: 90px;
}

.chartbg {
  border: 1px solid #bd6d29;
  width: 60%;
}


.chart-legend li span{
    display: flex;
    width: 12px;
    height: 12px;
    margin-right: 5px;
}
</style>
