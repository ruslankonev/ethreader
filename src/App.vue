<template>
  <div id="app">
    <v-app>
      <navigation/>
      <home/>
    </v-app>
  </div>
</template>

<script>
import Home from '@/components/home'
import Navigation from '@/components/static/navigation'
export default {
  name: 'App',
  components : {
    'home': Home,
    'navigation': Navigation
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Orbitron');
@import url('https://fonts.googleapis.com/css?family=Montserrat');
@import url('https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Material+Icons');

/* Generated by Glyphter (http://www.glyphter.com) on  Fri Feb 16 2018*/
@font-face {
    font-family: 'Glyphter';
    src: url('./assets/fonts/Glyphter.eot');
    src: url('./assets/fonts/Glyphter.eot?#iefix') format('embedded-opentype'),
         url('./assets//fonts/Glyphter.woff') format('woff'),
         url('./assets/fonts/Glyphter.ttf') format('truetype'),
         url('./assets/fonts/Glyphter.svg#Glyphter') format('svg');
    font-weight: normal;
    font-style: normal;
}
[class*='icon-']:before{
	display: inline-block;
   font-family: 'Glyphter';
   font-style: normal;
   font-weight: normal;
   font-size:80px;
   line-height: 1;
   -webkit-font-smoothing: antialiased;
   -moz-osx-font-smoothing: grayscale;
   display: block;
   background: -webkit-linear-gradient(to left, #6700c7 0%, #aa04b9 100%);
   background: linear-gradient(to left, #6700c7 0%, #aa04b9 100%);
   -webkit-background-clip: text;
   -webkit-text-fill-color: transparent;
}
.icon-decentralized:before{content:'\0041';}
.icon-upload:before{content:'\0042';}
.icon-intellectual-property:before{content:'\0043';}
.icon-payment:before{content:'\0044';}
.icon-selling:before{content:'\0045';}
.icon-smart-contract:before{content:'\0046';}
.icon-rewards:before{content:'\0047';}
.icon-ecosystem:before{content:'\0048';}
.icon-e-reading:before{content:'\0049';}

body {
  font-family: 'Muli', 'Helvetica', 'Arial', 'sans-serif';
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Montserrat', 'Catamaran', 'Helvetica', 'Arial', 'sans-serif';
  font-weight: 200;
  letter-spacing: 1px;
}

.primary-gradient {
  background: rgba(103,0,199,1); /* Old browsers */
background: -moz-linear-gradient(left, rgba(170,4,185,1) 0%, rgba(103,0,199,1) 100%);
background: -webkit-linear-gradient(left, rgba(170,4,185,1) 0%,rgba(103,0,199,1) 100%);
background: linear-gradient(to right, rgba(170,4,185,1) 0%,rgba(103,0,199,1) 100%);
}

.primary-color {
color: rgb(103,0,199); /* Old browsers */
color: -moz-linear-gradient(left, rgba(170,4,185,1) 0%, rgba(103,0,199,1) 100%);
color: -webkit-linear-gradient(left, rgba(170,4,185,1) 0%,rgba(103,0,199,1) 100%);
color: linear-gradient(to right, rgba(170,4,185,1) 0%,rgba(103,0,199,1) 100%);
}
</style>
