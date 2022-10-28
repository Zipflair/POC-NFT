# Zipflair Proof of Concept
This Zipflair proof of concept is just the start of what we will be trying to achieve. The Zipflair NFT Marketplace is an easy way to view, mint, manage or trade any Non Fungible Token implemented on top of the XRP Ledger. Currently we have different conecpts and trials all over the place, which we are looking to start piecing together in the near future.

## FrontEnd
In order to build our web app, we have chosen an awesome, React based theme, where it will require a minimum amount of work to style everything up - most of it is out of the box. The theme is fully customisable, responsive and has a modern NFT Marketplace feel. The theme of choice is Gigaland.

## Discovery
Currently we are exploring the different options to achieve our goal. For example, in terms of wallet integrations we have a few options to look at:

1. The minting service submits a NFTokenMint action with the external wallet account in the Issuer field; the external wallet must have the sender account in their AccountRoot.
2. The minting service submits a multi-sign transaction on behalf of the external wallet, meaning the external wallet has technically performed the NFTokenMint action; the external wallet must have the sender account in their SignersList. 
3. The minting service submits a NFTokenMint action, and then submits a NFTokenCreateOffer with a zero-Amount and the external wallet as the Destination.

**Please note this is currently a work in progress! :D**