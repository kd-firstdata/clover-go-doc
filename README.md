
![Clover](https://camo.githubusercontent.com/6c829b55aa7851e726e5fc0fd70448a0c00427b2/68747470733a2f2f7777772e636c6f7665722e636f6d2f6173736574732f696d616765732f7075626c69632d736974652f70726573732f636c6f7665725f7072696d6172795f677261795f7267622e706e67)

# Clover SDK for iOS POS Integration 
## Version
Alpha Release   
Version: 3.0.0  
## Overview
This SDK allows your iOS-based Point-of-Sale (POS) system to communicate with a Clover® payment device and process payments. 

It includes the SDK and an example POS. To work with the project effectively, you will need:

XCode 9.0.1+  
iOS 9.2 and above on your device  
Cocoapods 
  
To experience transactions end-to-end from the merchant and customer perspectives, we also recommend ordering a [Clover Go DevKit](http://cloverdevkit.com/collections/devkits/products/clover-all-in-one-developer-kit)
  
The SDK enables your custom mobile point-of-sale (POS) to accept card present, EMV compliant payment transactions. 
Clover Go supports two types of card readersa magnetic stripe, EMV chip-and-signature card reader and an all-in-one card reader that supports Swipe, EMV Dip, and NFC Contactless payments. The SDK is designed to allow merchants to take payments on iOS and Android smartphones and tablets.  

Core features of the  SDK for Clover Go include:  
1. Card Present Transactions – Transactions in which the merchant uses the approved card reader to accept physical credit or debit cards on a connected smartphone or tablet. The Clover Go platform supports the following payment options:  
   * **Magnetic Stripe Card** – A traditional payment card that has a magnetic stripe.  
   * **EMV Card** – A payment card containing a computer chip that enhances data security. Clover Go's EMV compliant platform enables the customer or merchant to insert an EMV card into the card reader.  
   * **NFC Contactless Payment** – A transaction in which a customer leverages an Apple Pay, Samsung Pay, or Android Pay mobile wallets by tapping their mobile device to the card readerNFC Contactless Payment – A transaction in which a customer leverages an Apple Pay, Samsung Pay, or Android Pay mobile wallets by tapping their mobile device to the card reader.    

The Clover Go SDK currently supports the following payment transactions:  
* **Sale** - A transaction used to authorize and capture the payment amount in at the same time. A Sale transaction is final and the amount cannot be adjusted. 
* **Auth** - A transaction that can be tip-adjusted until it is finalized during a batch closeout. This is a standard model for a restaurant that adjusts the amount to include a tip after a card is charged.  
* **Void** - A transaction that cancels or fully reverses a payment transaction. 
* **Refund** - A transaction that credits funds to the account holder.  
* **PreAuth** - A pre-authorization for a certain amount. 
* **PreAuth Capture** - A Pre-Auth that has been finalized in order to complete a payment (i.e., a bar tab that has been closed out).   
* **Partial Auth** - A partial authorization. The payment gateway may return a partial authorization if the transaction amount exceeds the customer’s credit or debit card limit.  
* **Tip Adjust** - A transaction in which a merchant takes or edits a tip after the customer’s card has been processed (i.e., after the initial Auth transaction).


