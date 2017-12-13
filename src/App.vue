<template>
  <div id="app">
    <!-- <HelloWorld/> -->
    <Cabecera/>  
    <Menu/>
    <Banner/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld'
import 'vue-awesome/icons'
import Menu from './components/Menu'
import Cabecera from './components/Cabecera'
import Banner from './components/Banner'


export default {
  name: 'app',
  components: {
    Menu,
    Cabecera,
    Banner
    // HelloWorld
  }
}
</script>

<style>
/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, font, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: transparent;
}
body {
  line-height: 1;
  font-family: 'Roboto', helvetica, sans-serif
}
ol, ul {
  list-style: none;
}
blockquote, q {
  quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
 
/* No olvides definir estilos para focus */
:focus {
  outline: 0;
}
 
/* No olvides resaltar de alguna manera el texto insertado/borrado */
ins {
  text-decoration: none;
}
del {
  text-decoration: line-through;
}
 
/* En el código HTML es necesario añadir cellspacing="0" */
table {
  border-collapse: collapse;
  border-spacing: 0;
}
input, textarea, select, button {font-size: 100%;font-family: inherit;}
</style>
