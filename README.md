# scrollxustis

This repo includes all files of the scrollxustis NFTs deployment on Scroll Mainnet.

## Contract address:
| Address                                          | Block Explorer                                                                |
|----------------------------                      |----------------------------------------------                                 |
| _0x9F5a001a1beF7779E93433170a30F08f21F4373C_ | **https://scrollscan.com/address/0x9f5a001a1bef7779e93433170a30f08f21f4373c** |


## Minting:


To mint your ***scrollxusti***:

1. Copy and paste the code in the [ERC721.sol](https://github.com/joansajoansa/scrollxustis/blob/main/ERC721.sol) file into the [Remix IDE](https://remix.ethereum.org/) text editor.

2. Compile it in the ***Solidity Compiler*** tab (remember selecting the _0.8.9+commit.e5eed63a_ compiler).

3. Go to the ***Deploy & run transactions*** tab.

4. Connect your Metamask by selecting "_Injected Provider - Metamask_" in the ***ENVIRONMENT*** field.
  
5. Paste the contract address <sub> ( 0x9F5a001a1beF7779E93433170a30F08f21F4373C )</sub> into the "_At address_" input field.
   
   The "_At address_" button should light up: Click it!

6. Scroll down to the ***Deployed Contracts*** section and click the right-pointing arrow next to the <sub>"SCROLLXUSTIS AT 0X9F5...4373C"</sub> contract to expand and see the **available functions** to interact with it.

7. Click on the **Mint** function, and sign the transaction!

8. **You are done!** Go to your favourite Scroll [NFT Marketplace](https://www.goerli.zkmarkets.com/scroll-mainnet/collections/0x9f5a001a1bef7779e93433170a30f08f21f4373c) and see which ***scrollxusti*** you have collected.

## About the "Art"

The collection represents my first algorithmically generated "PFP" set.

Each PFP was handpicked between 666 algorithmically generated combinations of the available traits, and then [inscribed](https://ordinals.com/inscription/540d62becfbde3bb3d89b069c1ae80272879e2b9c8b98d3b916fea18f6690b09i0) on the Bitcoin network using the [ord implementation](https://github.com/ordinals/ord) on a [Bitcoin Core](https://bitcoin.org/en/bitcoin-core/) full node.

I know they're lame, therefore their name **xustis** (which means "bullshits" in my "yet to be invented" own language...)

The point was to learn creating some pixel-art traits, exporting them independently and adapt some code to have my own generatively created collectibles, **and then storing it on the Bitcoin network for eternity**.

In motive of the [Scroll Origins campaing](https://scroll.io/developer-nft/check-eligibility), I decided to create some Metadata associated to each of them: upload it to IPFS, and deploy a collection of ERC721 tokens pointing to my [inscribed images](https://ordinals.com/content/540d62becfbde3bb3d89b069c1ae80272879e2b9c8b98d3b916fea18f6690b09i0) (which should be visible by anyone running a bitcoin full node with the ord indexing protocol).
