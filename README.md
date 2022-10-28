# Zipflair Proof of Concept
The Zipflair NFT Marketplace is an easy way to view, mint, manage or trade any Non Fungible Token implemented on the XRP Ledger. Until now our research has only successfully test on other blockchains, as explained in our proposal Ripple's competitors gas fees or network issue have lead us to believe XRPL would be the ideal solution for a low-cost high transaction ledger for trading NFTs as we intend to at Zipflair.

Due the to the extremely high number of cross-border transactions Zipflair will be processing, Zipflair plans to use XRP as the base currency in which all products are list by price in XRP and the users local fiat currency. 

## FrontEnd
Zipflair aims to merge traditional stock media marketplaces with an NFT advantage. The key target audience will have experience using stock media websites, therefore it is important to design the front end in a way that consistant with what they're comfortable with. The inital designs are expressed in the pitch deck and at Zipflair.com. The Front-end and UX/UI will be updated and improved consinderably during the course of this project.

## Discovery
Currently we are exploring the different options to achieve our goal. For example, in terms of wallet integrations we have a few options to look at:

1. The minting service submits a NFTokenMint action with the external wallet account in the Issuer field; the external wallet must have the sender account in their AccountRoot.
2. The minting service submits a multi-sign transaction on behalf of the external wallet, meaning the external wallet has technically performed the NFTokenMint action; the external wallet must have the sender account in their SignersList. 
3. The minting service submits a NFTokenMint action, and then submits a NFTokenCreateOffer with a zero-Amount and the external wallet as the Destination.

XRPL NFTs are in there infancy in comparison to most other NFT blockchains. Development on XRPL will require considerably more R&D, however the benefits of partnering with a company that provides ODL, low transaction fees and can handle the sort of volume of content and transactions Zipflair will be processing when it reaches just 0.1% of the total stock media market share, makes this project massively appealing for both parties.
