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

### NFT Community
* Link: https://flipsidecrypto.xyz/edit/queries/e3cced65-01d9-48b9-b164-71a2675e3990
