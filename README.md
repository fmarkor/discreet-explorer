# Experimental Discreet Explorer
A simple, experimental explorer for the Discreet cryptocurrency network.

**This project should not be considered final or even a good example of how to do an explorer. This is a primitive, very early experimental explorer, to serve data from an experimental, currently closed-off testnet. This project polls the JSON-RPC API and will therefore not have the speed advantages of a ZMQ-implementation. It could work for days, it could decide to fry our machine. Who knows?**

Discreet Explorer utilizes:
`get_block_count`
`get_block_hash_by_height`
`get_block_header_by_height`
`get_block`
`get_block_hash`
`get_outputs`
`get_transactions`
`get_transaction`
`get_transaction_count`
`get_private_output_count`
`get_blockchain`
`get_raw_transaction`

Fees, a proper mempool, and other things, are to-be-implemented. So to reiterate: *highly experimental*.


*This is a personal project, not affiliated directly with Discreet.*
