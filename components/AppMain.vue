<template>
  <div class="main">
    <picture class="cam">
      <img srcset="../assets/task-2-image-ground.jpg" />
    </picture>
    <picture class="overlayed-cam">
      <img srcset="../assets/task-2-image-over.png" />
    </picture>
    <div class="content">
      <h1 class="font-weight-bold">Wir zeigen Ihre Starken!</h1>

      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
        velit esse cillum dolore eu fugiat nulla pariatur.<br /><br />
        Rerum minima voluptatem, itaque voluptates modi quidem, ad, possimus
        asperiores sapiente alias cum provident illo odio rem veniam maiores
        expedita accusantium beatae! Lorem ipsum, dolor sit amet consectetur
        adipisicing elit.
      </p>

      <button>Ablouf</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "scss/custom";

button {
  background-color: #155388;
  border: none;
  border-radius: 4px;
  color: #fff;
  height: 38px;
  padding: 4px;
  width: 80px;
}

.cam,
.overlayed-cam {
  display: none;
}

.content {
  align-content: center;
  background-color: #fff;
  flex-direction: column;
  font-size: 20px;
  justify-content: center;
  height: auto;
  padding: 8px 32px 8px 32px;
  width: 90%;
}

@include media-breakpoint-up(lg) {
  .cam {
    display: block;
    float: left;
    position: relative;
    width: 70.11%;
    z-index: 1;
  }

  .overlayed-cam {
    display: block;
    float: left;
    position: absolute;
    width: 47.61%;
    z-index: 3;
  }

  .content {
    display: flex;
    background-color: #fff;
    border-radius: 2px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    font-size: 18px;
    height: 600px;
    margin-top: 20px;
    padding: 32px 40px 32px 40px;
    position: absolute;
    transform: translate(82%, 8%);
    width: 600px;
    z-index: 2;
    -ms-transform: translate(82%, 8%);
  }

  .main {
    left: 0;
    margin-top: 20px;
    position: relative;
    top: 0;
    width: 100%;
  }

  img {
    height: auto;
    max-width: 100%;
    right: 0px;
  }
}
</style>
