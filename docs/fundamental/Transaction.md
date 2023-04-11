In Lineage, a transaction is a request made by a user to perform some action on an NFT metadata, such as updating or creating a new metadata. The transaction includes information such as the user's public key, the NFT's data key, and the content of the metadata to be updated or created.

Once the transaction is initiated, it is broadcasted to the network for validation. The validator nodes verify the transaction by checking the user's signature and ensuring that the requested action is valid. If the transaction is deemed valid, it is recorded in the transaction table along with a reference to the latest metadata CID, which acts as a receipt for the transaction.

The metadata is then updated by creating a new IPFS DAG with the updated metadata content and linking it to the previous CID. The new CID is then stored in the metadata table as the latest metadata for the NFT.
