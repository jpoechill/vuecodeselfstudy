<template>
    <div class="pages-wrapper">
      <div class="container">
        <div class="row pages-row-padding">
          <div class="col-md-12">
            <p class="pages-header-padding">
              <span class="pages-header-text">
                Style Guide
              </span>
            </p>
            <p class="pages-row-body">
              This page describes the style guide for the website. Don't worry too much about whether you've followed it exactly -- the content is collaboratively edited and it's easily adjusted.
            </p>
          </div>
          <div class="col-md-12">
            <p class="pages-header-padding">
              <span class="pages-header-text">
                Content Style
              </span>
            </p>
            <p class="pages-row-body">
              For readability:
              <br>
              <ul>
                <li>Break paragraphs up into a few sentences each.</li>
                <li>Include many code examples.</li>
                <li>If a tutorial has too many steps, consider breaking out some of the content into a new tutorial. (There is no limit to the number of tutorials that can be added.)</li>
                <li>Code blocks are defined by surrounding the code in triple backticks. A language can be specified immediately after the first triple backticks. See the source code of this page for an example.</li>
              </ul>
            </p>
          </div>
          <div class="col-md-12">
            <p class="pages-header-padding">
              <span class="pages-header-text">
                Coding Standards
              </span>
            </p>
            <p class="pages-row-body">
              For consistency and readability:
              <br>
              <ul>
                <li>Please keep code very neat and indented correctly.</li>
                <li>Code should generally be indented with four spaces (Python, JS, HTML, CSS, YAML, etc.), except for languages like Ruby, Elixir, and lisps, which can be two-spaced.</li>
                <li>Follow <a href="https://www.python.org/dev/peps/pep-0008/">PEP 8</a> when writing code examples in Python.</li>
                <li>Be sure that your code editor reads .editorconfig files. Editorconfig plugins are available for all major code editors. (Ask Josh if you would like help installing an editorconfig plugin.)</li>
              </ul>
              Additionally, for JavaScript:
              <br>
              <ul>
                <li>Semicolons should be used.</li>
                <li>Prefer ES6 syntax when possible, but feel free to include ES5 equivalents.</li>
              </ul>
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

