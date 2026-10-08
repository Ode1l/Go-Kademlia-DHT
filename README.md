# Go Kademlia DHT

Undergraduate thesis by Jiaheng Li, Henan University, 2022.

A Go implementation of Kademlia peer discovery, integrated with a torrent-download session. The original Chinese thesis is provided below; this README is its English introduction.

## Original thesis

- [Read the original PDF](docs/Go-Kademlia-DHT-Undergraduate-Thesis-Chinese.pdf)
- [Download the original Word document](docs/Go-Kademlia-DHT-Undergraduate-Thesis-Chinese.docx)

**Original title:** Design and Development of the Kademlia Network Protocol Based on Go Language.

## What I implemented

- PING, FIND_NODE, GET_PEERS and ANNOUNCE_PEER RPCs.
- XOR-distance routing, node discovery and peer management.
- Concurrent queries using Go goroutines.
- Session configuration and integration for torrent downloading.

## Results and evidence

The thesis records peer lookup results, Wireshark packet captures and an Ubuntu torrent download using the DHT integrated into a third-party download tool. My DHT implementation and the reused download components are separate contributions.

This repository currently contains the thesis, not a standalone source release. It does not claim that I independently implemented the complete BitTorrent stack. The original documents retain their Chinese text and academic cover page; only filenames were changed for readability.
