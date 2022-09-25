<template>
  <div class="layout">
    
    <slot/>
  </div>
</template>

<style>
body {
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
  background-color: #5E615D;
}

.layout {
  max-width: 760px;
  margin: 0 auto;
  margin-top: 7em;
  padding-left: 20px;
  padding-right: 20px;
  border-radius: 30px;
}


</style>
