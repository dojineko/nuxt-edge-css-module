<template>
  <div>
    <div class="base" :class="$style.styledByCssModules">
      EXPECT BLUE (styled by CSS Modules)
    </div>
    <div class="base styledByScopedCSS">
      EXPECT BLUE (styled by Scoped CSS)
    </div>
  </div>
</template>

<style>
.base {
  color: red;
  font-size:32pt;
}
</style>

<style module>
.styledByCssModules {
  color: blue;
}
</style>

<style scoped>
.styledByScopedCSS {
  color: blue;
}
</style>
