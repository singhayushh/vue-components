<template>
    <header>
      <div class="contain">
          <div class="logo">deGRASSE</div>
          <nav>
            <ul>
              <li>How it works</li>
              <li>Use Cases</li>
              <li>Industries</li>
              <li>Resources</li>
              <li>Pricing</li>
            </ul>
            <Button text="Contact Us"/>
          </nav>
      </div>
    </header>
</template>

<script>
import Button from '../ui/Button'

export default {
  name: 'Header',
  components: {
    Button,
  }
}
</script>

<style scoped>
  header, .contain {
    height: 100px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .contain {
    padding: 0px 60px;
  }
  .logo {
    font-weight: 600;
  }
  nav, ul {
    display: flex;
    align-items: center;
  }
  ul li {
    list-style: none;
    margin-right: 40px;
  }
</style>
