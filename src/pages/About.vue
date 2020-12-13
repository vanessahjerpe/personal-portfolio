<template>
  <Layout>
    <div class="about">
      <div class="about-text">
        <h1>About Me</h1>
        <p>
          My name is Vanessa Hjerpe and I love 3d modeling and has done so since
          I was young. My main problem was that I didn't have a computer back
          then but that has now changed. Now I am making 3d models everyday as
          comissions, selling on Gumroad and other fun things.
        </p>
      </div>
      <div class="about-photo">
        <g-image src="~/assets/images/person.jpg" width="300" />
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "About Me",
  },
};
</script>

<style lang="scss" scoped>
.about {
  &-text {
    text-align: left;
  }
}
@media screen and (min-width: 768px) {
  .about {
    display: flex;
    flex-wrap: wrap;
    &-text {
      margin-right: 30px;
      max-width: 350px;
    }
  }
}
@media screen and (min-width: 1024px) {
  .about-text {
    margin-right: 50px;
    max-width: 600px;
  }
}
</style>

