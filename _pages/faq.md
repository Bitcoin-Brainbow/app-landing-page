---
layout: page
title: Frequently Asked Questions
include_in_header: true
---

# A frequently asked questions (FAQ) list
Here you can find answers ... 
<br>

### What is WarpWallet?

WarpWallet is a deterministic Bitcoin key generator that uses scrypt. 

Brainbow generates a "WarpWallet master private key" and derives everything from it.

More information about WarpWallet can be found [here](https://keybase.io/warp/).



### Is it possible to use dice rolls to generate my passwords? 

Sure. There are many ways to generate a "horse battery staple" – to generate a high-entropy passwords. 

We recommend using the [Diceware Password Generator](https://diceware.dmuth.org/).


### Is it possible to load my Brainbow wallet into another wallet?

Yes. Compatibility with other wallets is possible by exporting your wallet's BIP32 master private key using the Wallet Import Format (WIF) or using the BIP39 mnemonic (the 12 recovery words) and importing it in another wallet.  
<br>
Be very careful when working with unencrypted private key material.

### What does stateless?

The master private key is derived from the given salt and passphrase every time you use load the wallet.

All past and unconfirmed transactions are downloaded from the electrum server. 
The transaction history is reconstructed every time you use it. 

The same applies when using BIP39 seeds instead of salt/password credentials.

### Can a wallet be tracked or associated with a specific user? 

No. 


### Is the passphrase the same as a seed phrase?

No. A seed phrase usually means a 12 or 24 word combination of words taken from the BIP-39 word list. 
 
Also, do not confuse it with the BIP-39 passphrase which adds a extra layer of security to the 12 or 24 word mnemonic. 


### 
