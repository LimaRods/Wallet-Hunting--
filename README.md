# Wallet Hunting 🕵🏻 🪂 

* All datasets from each perpetua protocol will be consolidated into a final dataset. Each dataset has the following schema:
    - | unique trader | platform | blockchain | vol_all_platform | interaction_coun | last_interact_date (in the last 180 days) | activity (in the last 180 days)
* The file *pipeline.ipynb* is used to clean, prepare and consolidate all outputs from each protocol

## Sources
### Vertex
* Code: https://dune.com/queries/3319571?blockchain=arbitrum&category=essentials
* Dataset: you can see the physical data set in this folder "dataset/traders_vertex.xslx"

### HMX
* Code: https://dune.com/queries/3322162
* Dataset: you can see the physical data set in this folder "dataset/traders_hmx.xslx"

### GMX
* https://dune.com/queries/3326970?sidebar=none

### DyDx
* https://dune.com/queries/3350149

### GNX
* https://dune.com/queries/3329779?category=decoded_project&namespace=gains&blockchains=arbitrum

### Syntetix
* https://dune.com/queries/3331775?category=abstraction&namespace=synthetix&table=perpetual_trades&blockchains=optimism

### MUX
* https://dune.com/queries/3331840

### LVL
* https://dune.com/queries/3329599
  
###  AEEVO
* https://dune.com/queries/3332234

### AEVO
* https://dune.com/queries/3351533

### NFT Community
* Link: https://flipsidecrypto.xyz/Rodolfo-Lima/nft-communities-iIMSul

### Starknet Bridge
* link: https://dune.com/queries/3343404

### LProviders (Curve and Uniswap)
* link: https://flipsidecrypto.xyz/Rodolfo-Lima/nft-communities-iIMSul

### ETH Stakers (Lido and Rocket Pool)
* link: https://flipsidecrypto.xyz/Rodolfo-Lima/nft-communities-iIMSul

### Governance(DEX/blockchains/Lending):
* link :https://flipsidecrypto.xyz/Rodolfo-Lima/whale-hunters-iIMSul

### Optimism Governance
* Link: https://dune.com/queries/3349830

### Gitcoin Grants
* Link: https://dune.com/queries/3351720
