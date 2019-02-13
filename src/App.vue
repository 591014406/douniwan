<template>
  <div id="app">
    <div id="nav">
      <router-link to="/home">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
@charset "utf-8";

/*====================CSS Reset====================*/
header,
footer,
canvas,
summary,
details,
nav,
section,
main,
article,
aside,
figure,
figcaption {
  display: block;
}
body,
h1,
h2,
h3,
h4,
h5,
h6,
p,
a,
img,
input,
ul,
li,
ol,
dl,
dt,
dd,
header,
footer,
canvas,
summary,
details,
nav,
section,
main,
article,
aside,
figure,
figcaption {
  padding: 0;
  margin: 0;
}
img {
  display: block;
  border: 0;
}
ul,
ol {
  list-style: none;
}
input {
  outline: none;
}
body {
  font-size: 12px;
  color: #3e3e3e;
  font-family: Arial, Verdana, '微软雅黑', 'Heiti SC';
}
a {
  text-decoration: none;
  color: #909090;
}
a:hover {
  text-decoration: underline;
  color: #f60;
}
/*====================End Reset====================*/
/*====================Global====================*/
.g-wrapper {
  width: 1190px;
  margin: 0 auto;
}
.g-left {
  float: left;
}
.g-right {
  float: right;
}
/*====================End Global====================*/
</style>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
