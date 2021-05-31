<template>
  <div class="container">
    <div class="row">
      <div class="col-lg">
        <h1>Videoproduktion aus Osterreich</h1>
        <b>Imagevideos. Onlinepots. Reportagen.</b>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
          molestiae sunt voluptatum ipsam doloremque placeat! Illo cum facilis
          iusto maxime nobis expedita harum perspiciatis, voluptates veniam,
          dignissimos iure vel consequatur.
        </p>
        <button>Kontakt</button>
        <div class="contact">
          <p>
            +43 660 760 85 86<br />
            office@plusfilm.at <br />
            Mo-Fr: 09-18 Uhr
          </p>
        </div>
      </div>
      <div class="col-lg-6">
        <img class="camera" src="../assets/task-1.jpg" alt="Camera holding" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss">
button {
  background-color: #155388;
  border: none;
  border-radius: 4px;
  color: #fff;
  height: 38px;
  padding: 4px;
  width: 80px;
  margin-bottom: 16px;
}

h1 {
  font-weight: bold;
}

.container {
  max-height: 100vh;
}

.camera {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.contact {
  color: gray;
}
</style>
