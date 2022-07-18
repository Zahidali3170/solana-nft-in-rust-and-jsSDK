# single custom NFT mint with Rust
anchor init mint-nft
anchor deploy  //new program id
add new program id here---> file(libs.rs and anchor.toml)
anchor build &&  anchor deploy
yarn install
anchor run test
CXEP3GfqhRJAk9ybvNHWrAR3y9qugf6gKUczLPFQsNSC


## Metaplex java srcipt SDK
    findByMint
    findAllByMintLis
    loadNft
    findAllByOwner
    findAllByCreator
    uploadMetadata
    create_nft
    update
    printNewEdition

node version 14 install
npm install @metaplex-foundation/js @solana/web3.js

run comand ----> node --experimental-json-modules ./app.js