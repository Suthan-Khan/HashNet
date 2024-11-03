# HashNet
This is a distributed authentication system.

The way that HashNet works is that each member has a copy of other members IP adresses and ports. This is kept in a hash table and is shared with others. Regularly the memebers will send copies of themselves as serializable objects allnover the network and these will be compared tp authenticate the correct data and error corection will be aplies to any incorrect bits and data. The idea is to have a tamperproof record of data to prove or authenticate that certain data exists.
