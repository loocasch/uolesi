<template>
  <div>
    <Menu />
    <Slider />
    <Nuxt />
    <footer>
      <div class="container-fluid wrapper-small-box py-4">
        <div class="row">
          <div class="col-md-6 text-md-left text-center mb-md-0 mb-4">
            Copyright 2020 by uolesi.pl - All rights reserved.
          </div>
          <div class="col-md-6 text-md-right text-center">
            Realizacja:
            <a href="mailto:loocasch@gmail.com" class="text-default"
              >Łukasz Karpiński</a
            >
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
import Slider from '~/components/Slider'
import Menu from '~/components/Menu'

export default {
  components: {
    Slider,
    Menu,
  },
}
</script>
