# Zipflair Proof of Concept
Zipflair is a stock media NFT Marketplace, providing an easy way to view, mint, manage or trade any Non Fungible Token implemented on the XRP Ledger. So far our research has successfully test on other blockchains, such as Ethereum and Solano, high gas fees and network down time make the unrealistic prospects. XRPL would be the ideal solution for a low cost, high transaction marketplace for trading NFTs such as Zipflair.

Due the to the extremely high number of cross-border transactions Zipflair will be processing, the team plans to use XRP as the base currency in which all products are listed by price in XRP along with the users local fiat currency.

## FrontEnd
Zipflair aims to merge traditional stock media marketplaces with the NFT industry. The key target audience will have experience using stock media websites, therefore it is important to design the front-end in a way that is consistant with what they're comfortable with. The inital designs are expressed in the pitch deck and at Zipflair.com. The front-end and UX/UI will be updated and improved consinderably during the course of this project.

## Discovery
R&D into XRPL intergration with the Zipflair marketplace will require time and funding, although official development will only commence on this part of the project should funding be granted, the Technical Lead understands the process as outlined below:

1. The minting service submits a NFTokenMint action with the external wallet account in the Issuer field; the external wallet must have the sender account in their AccountRoot.
2. The minting service submits a multi-sign transaction on behalf of the external wallet, meaning the external wallet has technically performed the NFTokenMint action; the external wallet must have the sender account in their SignersList. 
3. The minting service submits a NFTokenMint action, and then submits a NFTokenCreateOffer with a zero-Amount and the external wallet as the Destination.

XRPL NFTs are in their infancy in comparison to most other blockchains supporting NFTs. Development on XRPL will require considerably more R&D, however the benefits of partnering with a Ripple such as ODL, low transaction fees and a network that can handle the sort of volume of content and transactions Zipflair will be processing when it reaches just 0.1% of the total stock media market share makes stock media NFTs on the XRPL massively appealing.
