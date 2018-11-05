<template>
  <div class="mymodule">
    <h1>Hello</h1>
  </div>
</template>

<style lang="sass">
$colors: (
  somecolor: #eac5c5,
  othercolor: #489de4
)

.mymodule
  background: map-get($colors, 'othercolor')

h1
  color: map-get($colors, 'somecolor')

</style>
