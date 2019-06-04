This is how to recover a 2013 Blockchain.info wallet. (wallet.aes.json)
This uses a propriety format that will ruin your day unless you use this method.

This assumes you know the password. For all of the following actions your should load the page and go offline. This might protect you from malware. This information is provided without warrantly, used at your own risk etc.

Decrypt the wallet.aes.json with 

https://github.com/pinheadmz/DecryptWallet (nothing else I found can do this nowadays). 

Take the private key it outputs and enter in the Bitcoin Address Base58 Decoder here http://lenschulwitz.com/base58

Enter that output into https://www.bitaddress.org 

Copy the Private Key WIF and use that to import it into your wallet of choice. https://electrum.org/#home will be fine. 








