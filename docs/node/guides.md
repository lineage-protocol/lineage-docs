---
sidebar_position: 2
---

# Guides

Setting up a local node is a great way to get started developing with Lineage before moving to a cloud-hosted node for production use-case.

## Things to note

As you're going through this section, make a note of the following variables:

| Variable  | Description                                                                                                   | Example                                                |
| --------- | ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| PeerID    | Cryptographically verifiable and unique reference to a specific peer within the overall peer-to-peer network. | `12D3KooWHBG9oaVx4i3vi6c1rSBUm7MLBmyGmmbHoZ23pmjDCnvK` |
| MultiAddr | Convention for encoding multiple layers of addressing information into a single “future-proof” path structure | `/ip4/127.0.0.1/tcp/9991/ws/p2p/`                      |

## Pre-requiresites

- [Docker](https://www.docker.com/) installed on your server or local machine.

## Installation and usage

1. Open your terminal, and clone the repository from branch `main`

```
git clone https://github.com/0x3Zero/fluence-node-custom
cd fluence-node-custom
```

2. Run docker image as daemon

```
docker-compose up -d
```

:::tip
To check if the container is already running, you can use docker-cli or docker desktop
:::

3. Take note of your MultiAddr dan PeerID. You`ll be needing it to deploy your meta-contract later on.

:::tip Note
You can check it inside your [docker-compose.yml](https://github.com/0x3Zero/fluence-node-custom/blob/main/docker-compose.yml)
:::

```
/ip4/127.0.0.1/tcp/9991/ws/p2p/12D3KooWHBG9oaVx4i3vi6c1rSBUm7MLBmyGmmbHoZ23pmjDCnvK
/ip4/127.0.0.1/tcp/9992/ws/p2p/12D3KooWRABanQHUn28dxavN9ZS1zZghqoZVAYtFpoN7FdtoGTFv
/ip4/127.0.0.1/tcp/9993/ws/p2p/12D3KooWFpQ7LHxcC9FEBUh3k4nSCC12jBhijJv3gJbi7wsNYzJ5
```

## Reference

- [MultiAddr](https://docs.libp2p.io/concepts/fundamentals/addressing/)
- [PeerID](https://docs.libp2p.io/concepts/fundamentals/peers/)
