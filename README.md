**In-Game Assets Tokenisation** 

> "TokenItemModified.cs" script pulls the public key of a token from the wallet.

> Passes the public key to "GetDataRoute" function in "TestingJsonPull.cs" which uses solscans API to get the json file of that particular nft.

> "ProcessJsonData" function which retrives the "uri" from the json file and passes it to "ProcessNftData" function through "getNftData" function which retrives the image of that nft

> The "CustomizeCharacter" function in "TestingJsonPull.cs" script is used to customize the character based on the data from the json file of the token.

> Currently we have used  metaplex code base for tokenisation (candy machine)

> **DUNE** - https://explorer.solana.com/address/2B2TTWK3Lcvs8g8YFdmsQyGqyy1efSGEJ2dz9wGFkcG2?cluster=devnet

> **MonkeyKing** - https://explorer.solana.com/address/8WTbzYTbcSys2BKEKSJhrSqUwMLbKNNL8JX42ZR6QJho?cluster=devnet

> **Rifle** - https://explorer.solana.com/address/22Hx3hwygaM8qNf2NXMS3LTMjTh7KvgKooGo3NfEMous?cluster=devnet

> **Pistol** - https://explorer.solana.com/address/HL5xkzHTSSefszQyF2i2FdChTBXbAKeggejELKvkEeU2?cluster=devnet
