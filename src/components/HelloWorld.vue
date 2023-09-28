<template>
  
    <meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="styles.css">
<title>Card</title>

<div class="wrapper">
  <div class="container" data-card="1">
    <div class="card">
      <div class="card-content">
        <h2 class="card-title">HAX PSU</h2>
        <img src="https://hax.camp/assets/haxBanner-01.png" alt="Card Image">
        <div class="description-toggle">
          <div class="description">Hax Camp 2022</div>
          <div class="toggle-button">Toggle Description</div>
        </div>
        <a class="details-link" href="https://hax.psu.edu">Details</a>
      </div>
    </div>
  </div>
</div>

<button class="duplicateButton">Duplicate Card</button>
<button class="toggleColorButton">Toggle Color</button>
<button class="changeTitleButton">Change Title</button>
<button class="deleteCardButton">Delete Last Card</button>
</template>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  background-color: white;
}

.wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.container {
  max-width: 400px;
  border: 4px solid navy;
  border-radius: 8px;
  margin: 16px;
  padding: 16px;
  background-color: white;
}

.container img {
  width: 100%;
  height: auto;
  border-radius: 10px;
}

.card-content {
  margin-top: 0;
  text-align: center;
}

.card-title {
  margin: 16px;
  text-align: center;
}

.description {
  margin: 4px;
}

.description-toggle {
  cursor: pointer;
}

.toggle-button {
  display: block;
  text-align: center;
  padding: 8px;
  border: 4px solid black;
  border-radius: 4px;
  margin-top: 16px;
  color: black;
  background-color: lightblue;
}
.details-link {
  display: none;
  margin-top: 16px;
  text-align: center;
}

.bg-toggle {
  background-color: darkgray;
}

.toggle-button:hover,
.toggle-button:focus {
  background-color: lightgray;
  color: black;
}

.hidden {
  display: none;
}
@media (max-width: 800px) {
  .button-details {
    display: none;
  }
}
</style>
