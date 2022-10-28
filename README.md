# Zipflair Proof of Concept
Zipflair is a stock media NFT Marketplace, providing an easy way to view, mint, manage or trade any Non Fungible Token implemented on the XRP Ledger. To date our research has successfully tested NFT minting on other blockchains such as Ethereum and Solano. However, high gas fees and network down time make these unrealistic prospects. XRPL would be the ideal solution, providing low fees for this large content, high transaction marketplace.

Due the to the extremely high number of cross-border transactions Zipflair will be processing, the team plans to use XRP as the base currency in which all content is listed by price in XRP along with the users local fiat currency.

## FrontEnd
Zipflair aims to merge a traditional stock media marketplace with the NFT industry. The key target audience will have experience using stock media websites, therefore it is important to design the front-end in a way that is consistant what our users will be comfortable with. The inital designs are expressed in the pitch deck and at Zipflair.com. The front-end and UX/UI will be updated and improved consinderably during the course of this project.

## Discovery
R&D into XRPL intergration with the Zipflair marketplace will require time and funding. Official XRPL intergration development will commence should funding be granted, the Technical Lead understands the process and is ready to begin with the developement required as outlined below:

1. The minting service submits a NFTokenMint action with the external wallet account in the Issuer field; the external wallet must have the sender account in their AccountRoot.
2. The minting service submits a multi-sign transaction on behalf of the external wallet, meaning the external wallet has technically performed the NFTokenMint action; the external wallet must have the sender account in their SignersList. 
3. The minting service submits a NFTokenMint action, and then submits a NFTokenCreateOffer with a zero-Amount and the external wallet as the Destination.

XRPL NFTs are in their infancy in comparison to most other blockchains supporting NFTs, therefore development on XRPL will require considerably more R&D. The benefits of partnering with Ripple such as ODL, low transaction fees and a network capable of handling the large volume of content and transactions Zipflair will be processing when it reaches just 0.1% of the total stock media market share, makes development on the XRPL massively appealing.
