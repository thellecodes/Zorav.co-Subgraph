### Zora.co Subgraph

A subgraph defines which data The Graph will index from Ethereum, and how it will store it.

This graph was created with (Thegraph Studio)[https://thegraph.com]

```{
  tokens(first: 5) {
    id
    tokenID
    contentURI
    metadataURI
  }
  users(first: 5) {
    id
    tokens {
      id
    }
    created {
      id
    }
  }
}```