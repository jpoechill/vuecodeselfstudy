<template>
  <div>
    <div class="fixed-top header-wrapper">
      <div class="container">
        <div class="row hidden-sm-down" style="padding: 10px 0px;">
          <div class="col-md-4 text-left" style="padding-top: 7px;">
            <img src="/css_logo_03.png" class="header-logo_image" alt="">
            <a href="/" class="header-logo_link">
              <span class="header-logo_top-bar">Code</span> 
              <span class="header-logo_bottom-bar">Self Study</span>
            </a>
          </div>
          <div class="col-md-8 text-right header-links_margin-top">
            <ul class="nav-list">
              <li><a href="/about/">About</a></li>
              <li><a href="/edu/">School</a></li>
              <li><a href="/contact/">Contact</a></li>
              <li id="header-links_contact-container">
                <a class="header-links_contact" href="/events/">Events</a>
              </li>
            </ul>
          </div>
        </div>
        <div class="row hidden-md-up" style="padding: 10px 0px;">
          <div class="col-md-12 text-left" style="display: flex; justify-content: center; padding-top: 7px;">
            <img src="/css_logo_03.png" class="header-logo_image" alt="">
            <a href="/" class="header-logo_link">
              <span class="header-logo_top-bar">Code</span> 
              <span class="header-logo_bottom-bar">Self Study</span>
            </a>
          </div>
          <div class="col-md-12 text-center header-links_margin-top">
            <ul class="nav-list">
              <li><a href="/about/">About</a></li>
              <li><a href="/edu/">School</a></li>
              <li><a href="/contact/">Contact</a></li>
              <li id="header-links_contact-container">
                <a class="header-links_contact" href="/events/">Events</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <nuxt/>
    <div>
      <div class="container footer-container">
        <div class="row footer-padding">
          <div class="col-md-12 text-center">
            <p>Code Self Study &copy; 2018<br>
            Study computer programming with like-minded people in Berkeley, California <br><br>
            Hosted by <a href="/sponsor/digital-ocean/" class="footer-link">Digital Ocean</a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>

</style>
