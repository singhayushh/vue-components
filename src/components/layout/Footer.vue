<template>
  <footer>
    <div class="contain">
      <div class="colophon-wrap">
        <h3>Company Name</h3>
        <p>With some description. <br />Of two lines</p>
      </div>
      <div class="links-wrap">
        <div class="links-section">
          <h4 class="links-title">Planets</h4>
          <ul>
            <li>Lorem</li>
            <li>Art</li>
            <li>Dolor</li>
            <li>Sit</li>
            <li>Amet</li>
            <li>Asteroids</li>
            <li>deGrasse</li>
          </ul>
        </div>
        <div class="links-section">
          <h4 class="links-title">Asteroids</h4>
          <ul>
            <li>Sit</li>
            <li>Amet</li>
            <li>Lorem</li>
            <li>Art</li>
            <li>Dolor</li>
            <li>Sit</li>
            <li>Amet</li>
            <li>Asteroids</li>
            <li>deGrasse</li>
          </ul>
        </div>
        <div class="links-section">
          <h4 class="links-title">Stars</h4>
          <ul>
            <li>Lorem</li>
            <li>You</li>
            <li>Ipsum</li>
            <li>Me</li>
          </ul>
        </div>
        <div class="links-section">
          <h4 class="links-title">Space</h4>
          <ul>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
            <li>Lorem</li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>


export default {
  name: 'Footer',
  components: {

  }
}
</script>

<style scoped>

  .contain {
    border-top: 1px solid rgba(0, 0, 0, 0.1);
    display: flex;
    justify-content: space-between;
  }
  .colophon-wrap {
    width: 30%;
  }
  .links-wrap {
    width: 70%;
    display: flex;
  }
  .links-section {
    width: 25%;
  }
  .links-title {
    font-weight: 600;
  }
  li {
    margin-top: 10px;
  }
</style>
