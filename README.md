<!-- START_METADATA
---
hide_table_of_contents: true
pagination_next: null
pagination_prev: null
---
END_METADATA -->

# Vipps Checkout for Shopify

The Vipps product page: [Vipps for Shopify](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/shopify/).

The plugin is available from the [Shopify app store](https://apps.shopify.com/vipps-checkout).

## Description

Official Vipps Checkout for Shopify. More than 4.3 million Norwegians use Vipps. Give them a fast and familiar shopping experience.

This is the official Vipps plugin that provides a direct integration with Shopify. Now you can let your customers choose Vipps directly in the checkout.

You can also do important back office tasks such as capture and refund directly from Shopify. Easy for your customer and easy for you.

Read [information from Vipps](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/shopify/) about the plugin.

## Vipps vs Vipps Checkout? What's the difference?

For the moment, there are two payment methods offered from Vipps available in Shopify, Vipps(called Vipps 2.0) and Vipps Checkout. Vipps Checkout is the latest one. Vipps 2.0 will be depreciated and replaced completely by Vipps Checkout in the future, so we suggest installing Vipps Checkout right away.

## Vipps Express Checkout

Vipps does not have a solution for Vipps Express Checkout (Vipps Hurtigkasse) in Shopify.
This is due to limitations on Shopify's side, and if Shopify makes changes that
make Vipps Hurtigkasse possible, we will add this functionality.

## Vipps Payment

When you enable this plugin, your customers will be able to choose Vipps as a payment method directly in the checkout. There is no need to go via a third party payment method. If your customer chooses Vipps, the customer fills in the contact information and is then asked to enter the phone number in the Vipps dialogue. Then the customer confirms the payment in the Vipps app. The order is now completed and are now stored in your Shopify store.

## How to get started

- Sign up to use Vipps på Nett [vipps.no](https://portal.vipps.no/login).
- After 1-2 days you will get an email with login details to Vipps Developer Portal, where you can get the API credentials
- Download and configure

## How to get Vipps account keys from Vipps Developer Portal

1. Sign in to the [Vipps Portal](https://portal.vipps.no/) using BankID.
2. Select the *Utvikler* ("Developer") tab and choose *Production Keys*. Here, you can find the merchant serial number (6 figures).
3. Click on *Show keys* under the *API keys* column to see *Client ID*, *Client Secret*, and *Vipps Subscription Key*.

See: [Getting Started](https://developer.vippsmobilepay.com/docs/vipps-developers/getting-started/), and the Vipps [FAQ](https://developer.vippsmobilepay.com/docs/vipps-developers/faqs/).

## Installation

### Step 1 - Preparations

Make sure you have easy access to the API keys, by logging in to [Vipps Portal](https://portal.vipps.no/) and find the correct API keys.

**Pro-tip**: If you are migrating from the old Vipps gateway (called Vipps 2.0 in Shopify), *don't uninstall it yet*, as we can autofill the API keys for you if it's installed. Makes it way easier for you to migrate. :)

### Step 2

Go to Shopify App store via [this link](https://apps.shopify.com/vipps-checkout?locale=nb) and install the *Vipps Checkout* app from there.

### Step 3

![Step 3](https://github.com/vippsas/vipps-checkout-shopify/raw/main/vipps-checkout-step-2.png?raw=true "Step 3")

### Step 4
![Step 4](https://github.com/vippsas/vipps-checkout-shopify/raw/main/vipps-checkout-step-3.png?raw=true "Step 4")

### Step 5
![Step 5](https://github.com/vippsas/vipps-checkout-shopify/raw/main/vipps-checkout-step-4.png?raw=true "Step 5")

### Step 6
![Step 6](https://github.com/vippsas/vipps-checkout-shopify/raw/main/vipps-checkout-step-5.png?raw=true "Step 6")

### Step 7
If you were migrating from Vipps 2.0 in Shopify, you can safely remove it from Shopify now.


## What do the different order statuses mean?

See [Shopify Order statuses with Vipps](https://developer.vippsmobilepay.com/docs/plugins-ext/shopify/shopify-faq/#what-do-the-different-order-statuses-in-shopify-mean-when-combined-with-vipps) for information regarding order statuses.

## How can I get help if I have any issues?

For issues with your Vipps for Shopify installation contact us via our [support system here](https://vipps-shopify.atlassian.net/servicedesk/customer/portal/3). For other issues you should contact [Vipps](https://developer.vippsmobilepay.com/docs/vipps-developers/contact/).

## Shopify FAQ (mainly Vipps for Shopify app)

See the [Shopify FAQ](https://developer.vippsmobilepay.com/docs/plugins-ext/shopify/shopify-faq/) we have created for more help with Shopify.

# Vipps FAQ

See the [Vipps FAQ](https://developer.vippsmobilepay.com/docs/vipps-developers/faqs/) for more help with Vipps.
