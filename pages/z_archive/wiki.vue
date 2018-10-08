<template>
    <div class="pages-wrapper">
      <div class="container">
        <div class="row pages-row-padding">
          <div class="col-md-12">
            <p class="pages-header-padding">
              <span class="pages-row-body">
                Programming Wiki
              </span>
            </p>
            <p style="padding: 0 0 0 16px; margin-left: -16px; border-left: 1px solid #ddd;">
              Code Self Study's programming wiki is being rebuilt. Please check back soon!
            </p>
            <p style="font-family: Caslon; font-size: 20px; padding: 80px 120px; background-color: #FFF; text-align: center;">
              “The most important property of a program is whether it accomplishes the intention of its user.”<br>
              <span style="font-style: italic;">
                ― C.A.R. Hoare
              </span>
            </p>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
  }
}
</script>

<style>

.pages-wrapper {
  background-color: #F7F7F7;
}

.pages-row-padding {
  padding: 30px 0px 0px;
}

.pages-header-padding {
  padding: 0 0 0px 0px; text-transform: uppercase; font-weight: bold;
}

.pages-header-text {
  font-size: 16px; padding: 3px 0px;
}

.pages-row-body {
  padding: 0 0 0 16px; margin-left: -16px; border-left: 1px solid #ddd;
}
</style>
