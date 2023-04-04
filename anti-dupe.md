How can we ensure that each card is received once and only once?

I think we can solve this problem in three locations: the sender, the receiver, and intermediate nodes. to solve this problem
in terms of the sender and nodes, we can just build a new protocol that will ensure no duplicates are sent, and the intermediate
nodes will not be able to create duplicates. that ways, we will make sure the receiver will always receive the unique cards. we can
also solve this problem in terms of the receiver. in this case, we don't control the input of the receiver. therefore, duplicate cards
may be received by the receiver, but in the receiver, we can build a new protocol that can get rid of the redundant cards and only process
unique messages.