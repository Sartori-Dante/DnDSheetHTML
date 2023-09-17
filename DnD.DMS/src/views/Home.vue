<template>
  <div class="d-flex flex-column" style="height: 100%; background-color: olive;">
    <div class="d-flex" style="height: 40%;">
      <div class="portrait d-flex align-center justify-center" variant="outlined"
      style="width: 20%;">
        <v-card style="height: 90%; width: 90%;">
          Portrait
        </v-card>
      </div>
      <div class="main-info" style="width: 50%;"></div>
      <div class="resources" style="width: 30%;"></div>
    </div>
    <div class="d-flex" style="height: 60%;">
      <div class="att-skills" style="width: 20%;"></div>
      <div class="saves-conditions" style="width: 20%;"></div>
      <div class="combat" style="width: 35%;"></div>
      <div class="items-feats" style="width: 25%;"></div>
    </div>
  </div>
</template>

<script>
  
</script>

<style>
.portrait{
  background-color: brown;
}

.main-info{
  background-color: aqua;
}

.resources{
  background-color: chartreuse;
}

.att-skills{
  background-color: blue;
}

.saves-conditions{
  background-color: blueviolet;
}

.combat{
  background-color: darkgoldenrod;
}

.items-feats{
  background-color: darkcyan;
}

.top-bar{
  height: 20hv;
}

.body{
  height: 80hv;
}

.no-background {
  background-color: transparent !important;
}
</style>