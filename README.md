**In-Game Assets Tokenisation** 

> "TokenItemModified.cs" script pulls the public key of a token from a wallet.

> Passes the public key to "GetDataRoute" function in "TestingJsonPull.cs" which uses solscans API to get the json file of that particular nft.

> "ProcessJsonData" function which retrives the "uri" from the json file and passes it to "ProcessNftData" function through "getNftData" function which retrives the image of that nft

> The "CustomizeCharacter" function in "TestingJsonPull.cs" script is used to customize the character based on the data from the json file of the token.
