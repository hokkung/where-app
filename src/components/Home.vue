<template>
  <b-container
    fluid
    class="full"
  >
    <b-row
      class="row "
      align-v="center"
    >
      <b-col class="left">
        <h1>LET’S BUILD YOUR </h1>
        <h1>WEBSITE TOGETHER! </h1>
        <p>Hi Guys, Exploring some new illustrations. Tools used : Adobe illustrator + Adobe Photoshop Hope you like it. Thank you.</p>
      </b-col>

      <b-col class="right">
        <b-img
          src="../assets/photo.png"
          fluid-grow
          alt="Responsive image"
        ></b-img>
      </b-col>
    </b-row>

  </b-container>
</template>

<script>
export default {
  name: "Home",
  props: {}
};
</script>

<style scoped>
.full {
  /* background: #505050; */
  min-height: 100%;
  display: flex;
  flex-direction: row;
}
.row {
  display: flex;
  align-items: stretch;
  /* background: #50ec45; */
  padding: 1px;
  min-width: 100%;
}
.left {
  min-width: 50%;
  padding-left: 10%;
  padding-bottom: 5%;
  font-family: "Source Sans Pro", sans-serif;

  /* background: #1c5f17; */
}
.left h1 {
  font-size: 60px;
  margin-top: -25px;
  color: #505050;
}
.left p {
  font-size: 20px;
  color: #707070;
}
.right {
  min-width: 50%;
  padding-left: 10%;
  padding-right: 10%;
  padding-bottom: 5%;
  /* background: #26b2ca; */
}
</style>
