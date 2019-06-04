This is how to recover a 2013 Blockchain.info wallet. (wallet.aes.json)
This uses a propriety format that will ruin your day unless you use this method.

This howto assumes you know the password to the wallet. 

For all of the following actions your should load the page and go offline. This might protect you from malware. This information is provided without warrantly, used at your own risk etc.

Decrypt the wallet.aes.json using  

https://github.com/pinheadmz/DecryptWallet (nothing else I found can do this nowadays, blockchain.info have helpfully removed their own tool). 


Take the private key it outputs, the one one alongside the bitcoin address and enter in the Bitcoin Address Base58 Decoder (the middle decoder) here http://lenschulwitz.com/base58

Copy and poste that output into https://www.bitaddress.org 

Scroll down, copy the "Private Key WIF" and you are done.

Use that key to import the address into your wallet of choice. https://electrum.org/#home will be fine, or try coinomi. 




Feel free to send me a tip: 3AmLzNUPZtTyHVApGrDx6x2u4t9jQwAzEw



