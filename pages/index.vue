<template>
  <body>
  <section class="section">
    <h2>
      <span class="material-icons">date_range</span> ordinary
    </h2>
    <div class="columns is-mobile">
      <!--
      <card
        title="Cat"
        icon="github"
        data-image="~static/cat.jpeg"
      >
        My favorite is <a href="inspire">
          Cat
        </a>
      </card>

      <card
        title="Responsive"
        icon="cellphone-link"
      >
        <b class="has-text-grey">
          Every
        </b> component is responsive
      </card>

      <card
        title="Modern"
        icon="alert-decagram"
      >
        Built with <a href="https://vuejs.org/">
          Vue.js
        </a> and <a href="http://bulma.io/">
          Bulma
        </a>
      </card>

      <card
        title="Lightweight"
        icon="arrange-bring-to-front"
      >
        No other internal dependency
      </card>
      -->
    </div>
<!--
    <change-color disp="■" />
    <br />
    <change-color />
    <br />
    <change-color fst-color="blue" snd-color="red" />
  -->
  <div class="bg_test" />
    <div>
      <i class="mdi mdi-face" />
      <i class="mdi mdi-nuxt" />
    </div>
    <span class="material-icons">double_arrow</span>
    <a href="cat"><span class="material-icons">pets</span></a>
    <a href="basket"><span class="material-icons">sports_basketball</span></a>

</div>
  </section>
</body>
</template>

<script>

export default {
  name: 'HomePage',

}
</script>
<style>
.bg_test {
    text-align:  center;    /* 文字中央寄せ */
    padding:  180px;        /* 余白指定 */
    width: 360px;           /* 幅指定 */
    border: solid 2px;      /* 枠線指定 */
    background-image: url("~@/assets/img/cat.jpeg");    /* 背景画像指定 */
    background-repeat:no-repeat
}
</style>
