<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>

<style lang="scss">
// ==========================================================================
// Reset
// ==========================================================================

//  1. Global
// ==========================================================================

html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font-style: normal;
  vertical-align: baseline;
  text-decoration: none;
  box-sizing: border-box;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}
body {
  line-height: 1;
  width: 100vw;
  height: 100vh;
  font-family: 'Lucida Console', Monaco, monospace;
}

//  2. List
// ==========================================================================

ol,
ul {
  list-style: none;
}
blockquote,
q {
  quotes: none;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
  content: '';
  content: none;
}

//  3. Tables
// ==========================================================================

table {
  border-collapse: collapse;
  border-spacing: 0;
}

//  4. Forms
// ==========================================================================

select {
  -moz-appearance: none;
  -webkit-appearance: none;
  background-color: transparent;
  width: 100%;
  display: block;
  color: #344a5e;
  font-size: 16px;
  padding: 5px 0;
  font-weight: 600;
  border: none;
}
input:focus,
select:focus,
button:focus,
label:focus {
  outline: none;
}

//  5. Before & After
// ==========================================================================

*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

//  6. links
// ==========================================================================

a,
a:hover,
a:focus,
a:visited {
  text-decoration: none;
  color: black;
}

//  END of RESET
// ==========================================================================

#app {
  display: flex;
  width: 100%;
  height: 100%;
}
</style>
