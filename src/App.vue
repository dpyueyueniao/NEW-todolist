<template>
    <HelloWorld></HelloWorld>
</template>

<script>
import HelloWorld from './views/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
@import './assets/base.less'; 
html,body,div,span,object,iframe,h1,h2,h3,h4,h5,h6,p,
blockquote,pre,abbr,address,cite,code,del,dfn,em,img,
ins,kbd,q,samp,small,strong,sub,sup,var,b,i,dl,dt,dd,
ol,ul,li,fieldset,form,label,legend,table,caption,tbody,
tfoot,thead,tr,th,td,article,aside,canvas,details,figcaption,
figure,footer,header,hgroup,menu,nav,section,summary,time,mark,audio,video {
margin:0;
padding:0;
}
h1,h2,h3,h4,h5,h6,em,i {
font-weight:100;
font-style:normal;
}
ul,ol,li {
list-style-type:none;
}

</style>
