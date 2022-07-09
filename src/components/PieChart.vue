<template>
  <pie-chart class="user" width=500px :data = "WasteDistri"></pie-chart>
</template>

<script>
export default {
  name: "PieChart",
  data() {
    return {
      WasteDistri: {
        "Paper & cardboard": '25%',
        "Glass": '25%',
        "Organic": '25%',
        "Plastic" : '25%',
        "Metal" : '15%',
        "Hazardous Wastes": '0.5%',
        "Other Wastes" : '1%'
    }
      }
}}
</script>

<style scoped>
.user{
  margin: auto;
  border: 3px solid grey;
}
</style> 