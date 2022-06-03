<template>
  <div>
    <slot name="header"></slot>
  </div>
  <br>
  <div>
    <slot name="body"></slot>
  </div>
  <br>
  <div>
    <slot name="footer"></slot>
  </div>
</template>

<style>
div {
  background: blue;
  color: white;
}
</style>
