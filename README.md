# Heartland Management Terminal WordPress Plugin

## ⚠️ DEPRECATION NOTICE

**This plugin is deprecated as of December 19, 2025 and is no longer actively maintained.**

### Migration Path

Please migrate to the **Global Payments WordPress solution** for continued support and enhanced features:

👉 **[Global Payments for WooCommerce](https://wordpress.org/plugins/globalpayments-gateway-provider-for-woocommerce/)**

For general WordPress payment integration, please visit:
- [Global Payments Developer Portal](https://developer.globalpay.com/)
- [Global Payments Support](https://developer.globalpay.com/support)

### Rationale

This plugin is being deprecated as part of the transition from Heartland Payment Systems to Global Payments. The Global Payments solution offers:
- Enhanced security features
- Broader payment method support
- Active development and support
- Improved integration with modern WordPress and WooCommerce versions

---

This management terminal exposes limited functionality to manage transactions through your WordPress installation. Current functionality may not be a one-to-one match for Portico Virtual Terminal.

## Description

This plugin allows merchants to manage transactions.

Features of Heartland Management Terminal:

* List transactions
* Manage transaction by:
  * void
  * refund

## Installation

1. Sign Up for an account @ developer.heartlandpaymentsystems.com if you haven't already
2. Download Gravity Forms
3. Install and activate Heartland Management Terminal plugin (see below sections)
4. Configure Heartland Management Terminal plugin under the Heartland > Options page:
   * Navigate to Settings to enter your API Keys provided by your Heartland Developer Portal Account

NEED ADDITIONAL HELP? Contact Us http://developer.heartlandpaymentsystems.com/support

### Using The WordPress Dashboard

1. Navigate to the 'Add New' Plugin page
2. Select `heartland-terminal.zip` from your computer
3. Click 'Upload'
4. Activate the Heartland Terminal plugin on the WordPress Plugin Dashboard

### Using FTP

1. Extract `heartland-terminal.zip` to your computer
2. Upload the `heartland-terminal.zip` directory to your `wp-content/plugins`
   directory
3. Activate the Heartland Terminal plugin on the WordPress Plugins dashboard

## Changelog

### 1.4.0

* Fixed plugin errors - Security Vulnerabilities
* Testes upto WordPress version 6.7

### 1.1.1

* Fixed hard-coded public API key on payments page

### 1.1.0

* Added ability to process credit cards

### 1.0.0

* Initial Release
