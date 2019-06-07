# WooCommerce Gateway Plugin for Lightning

Gateway plugin to accept Lightning payments at [WooCommerce](https://woocommerce.com) stores,
based on [Lightning Charge](https://github.com/Groestlcoin/lightning-charge).

## Installation

Requires PHP >= 5.6 and the `php-curl` and `php-gd` extensions.

1. Setup [Lightning Charge](https://github.com/Groestlcoin/lightning-charge).

2. [Download woocommerce-gateway-lightning.zip](https://github.com/Groestlcoin/woocommerce-gateway-lightning/releases/download/v0.2.6/woocommerce-gateway-lightning.zip)

3. Install and enable the plugin on your WordPress installation.

4. Under the WordPress administration panel, go to `WooCommerce -> Settings -> Checkout -> Lightning` to configure your Lightning Charge server URL and API token.

That's it! The "Groestlcoin Lightning" payment option should now be available in your checkout page.

## License

MIT
