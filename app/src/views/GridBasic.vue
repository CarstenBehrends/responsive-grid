<template>
  <div>
    <div class="container">
      <h1>Grid</h1>
      <h3>Default "col" columns, make them all equal width, staying on one row till the content breaks</h3>
      <div class="row">
        <div class="col">content</div>
        <div class="col">content</div>
        <div class="col">content</div>
        <div class="col">content</div>
        <div class="col">content</div>
        <div class="col">content</div>
        <div class="col">content</div>
        <div class="col">content</div>
      </div>
    </div>

    <div class="container">
      <h3>visibility utilities</h3>
      <div class="row">
        <div class="col hide-xs-only">hide-xs-only</div>
        <div class="col hide-ms">hide-ms</div>
        <div class="col hide-ms-only">hide-ms-only</div>
        <div class="col hide-xs show-ms">hide-xs show-ms</div>
        <div class="col hide-sm">hide-sm</div>
        <div class="col hide-sm-only">hide-sm-only</div>
        <div class="col hide-xs show-xl">show-xl</div>
        <div class="col hide-xs-only">hide-xs-only</div>
      </div>
    </div>

    <div class="container">
      <h3>default container, column size breakpoints</h3>
      <div class="row">
        <div class="col-xs-12 col-ms-10 col-sm-4 col-md-6 col-lg-8"></div>
        <div class="col-xs-12 col-ms-2 col-sm-8 col-md-6 col-lg-4"></div>

        <div class="col-xs-12 col-ms-2 col-sm-8 col-md-6 col-lg-4"></div>
        <div class="col-xs-12 col-ms-10 col-sm-4 col-md-6 col-lg-8"></div>
      </div>
    </div>

    <div class="container-narrow">
      <h3>narrow container, column size breakpoints</h3>
      <div class="row">
        <div class="col-xs-12 col-ms-10 col-sm-4 col-md-6 col-lg-8"></div>
        <div class="col-xs-12 col-ms-2 col-sm-8 col-md-6 col-lg-4"></div>

        <div class="col-xs-12 col-ms-2 col-sm-8 col-md-6 col-lg-4"></div>
        <div class="col-xs-12 col-ms-10 col-sm-4 col-md-6 col-lg-8"></div>
      </div>
    </div>

    <div class="container-fluid">
      <h3>fluid container, column size breakpoints</h3>
      <div class="row">
        <div class="col-xs-12 col-ms-10 col-sm-4 col-md-6 col-lg-8"></div>
        <div class="col-xs-12 col-ms-2 col-sm-8 col-md-6 col-lg-4"></div>

        <div class="col-xs-12 col-ms-2 col-sm-8 col-md-6 col-lg-4"></div>
        <div class="col-xs-12 col-ms-10 col-sm-4 col-md-6 col-lg-8"></div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "grid-basic"
};
</script>

<style scoped>
</style>