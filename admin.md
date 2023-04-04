How can we send commands ("SLEEP", "RESTART", "ARE-YOU-THERE", etc) to individual nodes in the network, 
rather than treat them as pass-through intermediaries?

the problem here we are trying to solve is that how can we let one individual node to recognize
if the messages that it receives are commands or just messages that it needs to pass through. one way to
solve this is very similar to what we have done during class. in the previous class, we have encountered a
problem that the other receiver computer does not know if it has received all the messages or not. how we solved
this problem is that we drew the unique index on the card and in the meanwhile drew out the number of the cards
the receiver is supposed to receive. in this case, we can do the same things. we can just create a marker on each card
and the marker represents if the card is a message or it is a command. if it is a command, the node will process the command
if it is a message, the node will pass it to the next node.