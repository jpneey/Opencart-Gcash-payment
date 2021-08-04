# Opencart-Gcash-payment
Gcash Opencart 3.x payment method

## Installation
- Upload the `admin` and `catalog` folder on the base directory of your store.
  - This does not override core files and it is compatible on any theme and other extensions. 
- Navigate to your administration dashboard then go to `extensions->payments` and then select `install`
- After installation, you can then check/update the extension's configuration from `extensions->payments->gcash`.

## Faq
- This extension mimics the `bank_transfer` payment method.
- Gcash payments are **not** processed on your checkout flow.
- This extension will only give gcash payment instructions (which can be edited on your dashboard) to your customer.
  - Customers will see the instructions upon **checking out** and on their **order email confirmation**. 

## Configuration
- Gcash Instructions: Instructions that will be given to the customer
  - ex: ** Please send your payment to: 09XX XXX XXXX ** 
