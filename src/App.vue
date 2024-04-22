<template>
  <router-view/>
</template>

<style>
body{
  background-color: #DBFF00;
  animation-name: rgb;
  animation-duration: 60s;
  animation-iteration-count: infinite;
}












@keyframes rgb{
  0%    { background-color: #DBFF00;}
  10%   { background-color: #95ff00;}
  20%   { background-color: #00ff2a;}
  30%   { background-color: #00ffae;}
  40%   { background-color: #006aff;}
  50%   { background-color: #002aff;}
  60%   { background-color: #8800ff;}
  70%   { background-color: #ff00fb;}
  80%   { background-color: #ff0090;}
  90%   { background-color: #ff000d;}
  100%  { background-color: #DBFF00;}
}

</style>
