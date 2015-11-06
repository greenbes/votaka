# Votaka

__Votaka__ is a voting platform for small and medium-sized organizations (smaller than 1,000 voting entities) that makes heavy use of the bitcoin blockchain for communication and verification. The primary goal of this project is to investigate various approaches to internet voting. It might (or might not) also result in working software.

Votaka should:
* Operate without requiring any particular server (I sometimes refer to this as "serverless", but that's an overstatement for now)
* Allow each voting entity to select their own client
* Support automated ballot certification, manual certification, or a mix of both

## What do I mean by "serverless"?

I often use the term _serverless_ when describing Votaka. This is a line in the sand that I realize is aggressive, given the current state of bitcoin.  

* The use of a central server is optional, based on the organization's acceptable latency and willingness to pay for messages to be posted to the blockchain
* No _particular_ central server is required.  Users 

One of the most appealing aspects of the blockchain is that it's a neutral, public resource that can be used to pass messages.  
