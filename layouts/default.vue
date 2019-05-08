<template>
  <div>
    <nuxt />
  </div>
</template>

<style>
html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid lightgreen;
  color: lightgreen;
  text-decoration: none;
  padding: 10px 30px;
  font-weight: 500;
}

.button--green:hover {
  color: black;
  background-color: lightgreen;
  text-decoration: none;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #4a9ecfad;
  color: #4a9ecfad;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
  font-weight: 500;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
  text-decoration: none;
}
</style>
