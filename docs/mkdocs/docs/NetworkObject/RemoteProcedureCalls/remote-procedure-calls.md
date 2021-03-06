# Remote Procedure Calls
Remote procedure calls (RPC) is a way to call functions over the network. So lets imagine that you (**ClientA**) had a method named **"Explode"** and I (**ClientB**) wanted to call that **"Explode"** method on your machine so that we both see the fireworks at the same time. Your main question might be:
> "Well how can I call that function so that we both can see the fireworks explode at the same time?"

The answer of course is by doing a Remote Procedure call. An RPC can be called on a specific client, all clients, buffered clients, etc. 
RPCs use a reliable protocol - They always come in the right order and reception of RPCs is confirmed.
To get you quickly started, check out the [Basic RPC Example](/GettingStarted/basic-rpc-example.md). Once you have gone through that example and consumed all of its educational value, feel free to brows the below links for more information.


* [Buffered RPCs](buffered-rpcs)
* [Sending RPC To Single Player](sending-rpc-to-a-single-player)
* [RpcArgs and RpcInfo Structs](rpcargs-and-rpcinfo-structs)
* [RPC Validation by Server](rpc-validation-by-server)
* [Replacing Previous Buffered RPCs](replacing-previous-buffered-rpcs)
+ [Clearing Buffered RPCs](clearing-buffered-rpcs)
