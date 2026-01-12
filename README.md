[![Latest Stable Version](http://poser.pugx.org/deadsimple/hyva-input-mask/v)](https://packagist.org/packages/deadsimple/hyva-input-mask) [![Total Downloads](http://poser.pugx.org/deadsimple/hyva-input-mask/downloads)](https://packagist.org/packages/deadsimple/hyva-input-mask) [![Latest Unstable Version](http://poser.pugx.org/deadsimple/hyva-input-mask/v/unstable)](https://packagist.org/packages/deadsimple/hyva-input-mask) [![License](http://poser.pugx.org/deadsimple/hyva-input-mask/license)](https://packagist.org/packages/deadsimple/hyva-input-mask) [![PHP Version Require](http://poser.pugx.org/deadsimple/hyva-input-mask/require/php)](https://packagist.org/packages/deadsimple/hyva-input-mask)

# Deadsimple Hyva Input Mask Module using AlpineJs Plugin

This module is a simple wrapper to integrate the input mask plugin from AlpineJs directly into your Hyvä theme and forms. It allows you to easily apply input masks to form fields, enhancing user experience and data validation.

## Installation

To install the module, follow these steps:

1. Install the module using Composer:

```bash
composer require deadsimple/hyva-inputmask
```

2. Enable the module:

```bash
bin/magento module:enable DeadSimple_HyvaInputMask
```

3. Run the setup upgrade:

```bash
bin/magento setup:upgrade
```

## Usage

To use the input mask plugin, you need to add the `x-mask` attribute to your input field. The value of the `x-mask` attribute should be a valid mask pattern. For example:

```html
<input type="text" x-mask="999-999-9999" />
```

This will apply a phone number mask to the input field, allowing only digits and formatting them as `999-999-9999`.

For more information on the available mask patterns and options, refer to the [AlpineJs Mask Plugin Documentation](https://alpinejs.dev/plugins/mask).

## License

This module is licensed under the MIT License. See the LICENSE file for more information.
