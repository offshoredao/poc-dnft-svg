# Proof of concept for dNFT using SVG
We see a new generation of the internet full of new possibilities. Where, your creativity is valued and your digital objects belong to you.
This repository will resignificate the concept of Metaverse. By proving interoperatibility among different NFT collections. 

## A case for using SVG to achieve interaperable dynamic NFTs. 

### First case: Decentraland wereables. 

Here we will prove the concept of using SVG technology to generate a dynamic NFT on Ethereum consuming metadata from external NFTs.  
On the first version we will mint on tesnet a `root_ERC-721` token with the field `animation_url` displaying one SVG image compused by 4 layers.


- Layer 1) `image_url` from `root_ERC-721` on Goerli, Ethereum Testnet.

- Layer 2) `image_url` taken `decentraland-wereable-1` on Polygon. 

- Layer 3) `image_url` taken `decentraland-wereable-2` on Polygon.

- Layer 4) `image_url` taken `decentraland-wereable-3` on Polygon.

![Screen Shot 2022-10-25 at 21 05 07](https://user-images.githubusercontent.com/65098295/197904247-1199aa48-73b1-4cb6-b13c-de54f9353574.png)

The result will be a 
The first and root image will be static and consuming  w. Using 1/4 of the final image.
For the other 3 layers, extra properties or metadata will be used, in order to point to 3 different sources of images.
Allowing the NFT holder to set three assets, which will be 3 separated layers over the root NFT Animation URL.
The Base NFT Image will be used as the base SVG Layer and will be immutable

![Diagrama sin título-POC-fp-dnft-svg drawio (1)](https://user-images.githubusercontent.com/11360704/197374318-9642c46c-0d6e-4604-a011-fe4704835d28.png)
