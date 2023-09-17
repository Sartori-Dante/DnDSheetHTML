<template>
  <v-app-bar class="d-flex align-center">
      <v-img class="mx-auto my-2" max-height="40" src="../../src/assets/dragon.png"></v-img>

      <v-btn dark color="blue" id="color-toggle">
          Color Grid
      </v-btn>  

  </v-app-bar>
</template>

<script>

// Get the button and the elements with the 'colorful' class
const toggleButton = document.getElementById('color-toggle');
const colorfulElements = document.querySelectorAll('.portrait.main-info.resources.att-skills.saves-conditions.combat.items-feats');

// Function to toggle the background color
function toggleBackgroundColor() {
  colorfulElements.forEach((element) => {
    element.classList.toggle('no-background');
  });
}

// Add a click event listener to the button
toggleButton.addEventListener('click', toggleBackgroundColor);

</script>



