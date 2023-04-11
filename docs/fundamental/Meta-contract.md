# Meta contract

Meta contract is a smart contract that acts as an intermediary between users and the Lineage node, allowing for the execution of automated tasks related to the metadata of Non-Fungible Tokens (NFTs). It provides a layer of abstraction between the user and the underlying network, enabling the user to interact with the NFT metadata in a more user-friendly and efficient manner.

Overall, the meta contract provides a powerful tool for managing NFT metadata on the network, enabling the creation of complex applications and workflows that take advantage of the unique properties of NFTs.

### What is Meta Contract?

Meta contract is a smart contract that is used to automate the execution of various tasks related to NFT metadata management. It acts as an intermediary between the users and the Lineage node, enabling the execution of metadata-related tasks on the network without the need for intermediaries or time loss. The meta contract is written in Rust programming language and deployed to the network as a wasm. It can perform various tasks, such as creating, updating, and deleting metadata, as well as managing access control to the metadata.

The meta contract is designed to be extensible, allowing developers to add new functionality as needed. It can be customized to fit the specific requirements of a given application or use case, making it a flexible tool for managing NFT metadata. Meta contract is based on Fluence service architecture.

### Purpose

The main purpose of the meta contract include creating, updating, and deleting NFT metadata, as well as managing access control to the metadata. It also facilitates the system boundary.

### Built in capabilities

The meta-contract in Lineage has a built-in library that allows it to interact with external data state using tools like curl and ipfs-cli. This allows the meta-contract to access and manipulate data outside of the blockchain network. For example, it can fetch data from a weather server using a curl command, and update the metadata based on the current weather of a location.

### Reference

- https://webassembly.org/
- https://github.com/0x3Zero/meta-contract-template
