function injectStyle (ssrContext) {
  require("!!../../../node_modules/extract-text-webpack-plugin/dist/loader.js?{\"omit\":1,\"remove\":true}!vue-style-loader!css-loader?{\"minimize\":true,\"sourceMap\":true}!../../../node_modules/vue-loader/lib/style-compiler/index?{\"vue\":true,\"id\":\"data-v-39ef5d26\",\"scoped\":true,\"hasInlineConfig\":false}!sass-loader?{\"sourceMap\":true}!../../../node_modules/vue-loader/lib/selector?type=styles&index=0!./dialog-delete.vue")
}
var Component = require("!../../../node_modules/vue-loader/lib/component-normalizer")(
  /* script */
  require("!!babel-loader!../../../node_modules/vue-loader/lib/selector?type=script&index=0!./dialog-delete.vue"),
  /* template */
  require("!!../../../node_modules/vue-loader/lib/template-compiler/index?{\"id\":\"data-v-39ef5d26\",\"hasScoped\":true}!../../../node_modules/vue-loader/lib/selector?type=template&index=0!./dialog-delete.vue"),
  /* styles */
  injectStyle,
  /* scopeId */
  "data-v-39ef5d26",
  /* moduleIdentifier (server only) */
  null
)

module.exports = Component.exports



//////////////////
// WEBPACK FOOTER
// ./src/components/nl/dialog-delete.vue
// module id = 2350
// module chunks = 0 1