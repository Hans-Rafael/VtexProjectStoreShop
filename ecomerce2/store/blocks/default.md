{
  "store.orderplaced": {
    "blocks": [
      "order-placed"
    ]
  },
  "store.account": {
    "blocks": [
      "my-account"
    ],
    "parent": {
      "challenge": "challenge.profile"
    }
  },
  "store.login": {
    "blocks": [
      "login-content#default"
    ]
  },
  "login-content#default": {
    "props": {
      "isInitialScreenOptionOnly": false,
      "defaultOption": 1,
      "showPasswordVerificationIntoTooltip": true,
      "optionsTitle": "login"
      /* "iconLabel": "login",
      "showIconProfile": true,
      "hideIconLabel": false */
    }
  },
  "product-summary.shelf": {
    "children": [
      "product-summary-add-to-list-button",
      "product-summary-name",
      "product-rating-inline",
      "product-summary-space",
      "product-summary-price",
      "product-identifier.summary",
      "add-to-cart-button"
    ]
  }
}