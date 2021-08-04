# Opencart-Gcash-payment
Gcash Opencart 3.x payment method

## Installation
- Upload the `admin` and `catalog` folder on the base directory of your store.
  - This does not override core files and it is compatible on any theme and other extensions. 
- Navigate to your administration dashboard then go to `extensions->payments`, find `gcash` then select `install`
- After installation, you can then check/update the extension's configuration from `extensions->payments->gcash`.

## Faq
- This extension mimics the `bank_transfer` payment method.
- Gcash payments are **not** processed on your checkout flow.
- This extension will only give gcash payment instructions (which can be edited on your dashboard) to your customer.
  - Customers will see the instructions upon **checking out** and on their **order email confirmation**. 

## Configuration
- Gcash Instructions: Instructions that will be given to the customer
  - ex: ** Please send your payment to: 09XX XXX XXXX **.
- Total: The checkout total that the order must reach before this payment method becomes active.
- Order Status: Order status to be set on every order after using this payment method.
- Geo Zone: Geo zones that should be used before this payment method becomes active.

## Download on Marketplace
https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=42444
