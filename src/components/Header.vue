<template>
  <div class="header">
    <h1>Cursos</h1>
    <hr />
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem sunt
      assumenda adipisci, nesciunt, soluta modi ex, possimus eos id doloremque
      doloribus. Blanditiis excepturi vitae?
    </p>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss">
.header {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 4rem 15rem 6rem 15rem;
}
hr {
  width: 5%;
  border: 1.5px solid #3434ff;
  background: #3434ff;
  margin: 1.5rem 0;
}
p {
  line-height: 1.6;
  text-align: center;
}
@media (max-width: 767.98px) {
  .header {
    margin: 4rem 10rem 6rem 10rem;
  }
  hr {
    width: 10%;
  }
}
@media (max-width: 575.98px) {
  .header {
    margin: 4rem 6rem 6rem 6rem;
  }
}
</style>
