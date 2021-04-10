<template>
  <Header />
  <HomePage />
  <Footer />
</template>

<script>
import Header from './components/layout/Header'
import HomePage from './components/pages/HomePage'
import Footer from './components/layout/Footer'

export default {
  name: 'App',
  components: {
    Header,
    HomePage,
    Footer,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

:root {
  --var-color-heading: #515151;
  --var-color-dark: #8A8A8A;
  --var-color-light: #FFFFFF;
  --var-padding-l: 60px;
  --var-padding-m: 60px;
  --var-button-background: #0090DA;
  --var-light-background: #F3F2F0;
  --var-shadow-color: rgba(0, 0, 0, 0.1);
}

body {
  height: 100%;
  width: 100%;
  font-size: 1rem;
  font-family: 'Poppins', sans-serif;
  color: var(--var-color-dark);
  background-color: var(--var-light-background);
}

h1, h2, h3, h4 {
  color: var(--var-color-heading);
}

h1 {
  font-size: 2.5rem;
}

h2 {
  font-size: 2rem;
}

h3 {
  font-size: 1.5rem;
}

h4 {
  font-size: 1.25rem;
}

li {
  list-style: none;
}

.span-1-of-1 {
  width: 100%;
  text-align: center;
  display: inline-block;
  vertical-align: middle;
  border-radius: 22px;
}

.span-1-of-2 {
  width: 50%;
  display: inline-block;
  vertical-align: middle;
  border-radius: 22px;
}

.span-1-of-3 {
  width: 33.33%;
  display: inline-block;
  vertical-align: middle;
  border-radius: 22px;
}

section {
  padding: 0 var(--var-padding-m);
}

.contain {
    padding: var(--var-padding-l) 0;
    width: 100%;
}

.short-text {
  max-width: 70%;
}

.card {
  margin: 4rem;
  padding: 1rem;
  border-radius: 1.2rem;
  background-color: #fff;
}

.flex {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.btn {
  display: inline-block;
  background: var(--var-button-background);
  color: var(--var-color-light);
  border: none;
  padding: 10px 20px;
  border-radius: 50px;
  cursor: pointer;
  text-decoration: none;
  font-weight: 600;
  box-shadow: 3px 3px 9px var(--var-shadow-color);
}

.btn-block {
  display: block;
  width: 100%;
}

.white-bg {
  background-color: var(--var-color-light);
}

.grey-bg {
  background-color: var(--var-light-background);
}

footer {
  display: block;
  padding: 0 var(--var-padding-m);
  background-color: var(--var-color-light);
}

</style>
