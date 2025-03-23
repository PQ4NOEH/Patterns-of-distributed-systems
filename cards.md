CAP theorem. your design choices has to prioritize availability or consistency.

State machine replication. Schneider 1990. achieves fault tolerance while guarantees strong consistency.

write-ahead log / Commit log. Provide durability whithout storage data strucutures to be flushed to the disk. Persist every state change as command to an append only log
