# Deweb Websites

This GitHub repository is a collection of DeWeb websites that can be used by people and tools to help users access websites stored on the Massa Blockchain. For more information about DeWeb, please visit the [Massa DeWeb Documentation](https://docs.massa.net/docs/deweb/home).

## Adding a Website

To add your DeWeb website to this repository, please follow these steps:

1. Create a new YAML file in the `websites` directory.
2. Name the file to match your website's name.
3. Ensure the file follows the format specified in `schema.yaml`.
4. Submit a pull request with your new file.
5. The pull request will be tested by the CI pipeline to ensure it is valid.
6. If your pull request is valid, it will be reviewed by the Massa team and merged.

### Example Website File

Here is an example of a website file:

```yaml
title: "Massa Explorer"
mns: "explorer.massa"
desc: "Official Massa blockchain explorer."
owner: "Massa Team"
contact:
  email: "support@massa.net"
category:
  - "Official"
  - "Infrastructure"
```

You can also take example on the existing websites in the 

websites

 directory.

### Valid Contact Information

A valid contact is required in the website file. The contact information can include an email, Discord, or Telegram handle. Here is the format for the contact section:

```yaml
contact:
  email: "example@example.com"
  discord: "username"
  telegram: "@username"
```

You must include at least one of the contact options in your website file.

### Categories

Each website must have at least one category from the list of available categories. Here are the available categories with descriptions:

| Category       | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| `Official`     | Massa Official websites (e.g., Explorer, MNS, etc.)                         |
| `Massa`        | Massa related websites (e.g., Massa specific explorers, Massa specific tools, etc.) |
| `DeFi`         | Decentralized Finance platforms (e.g., DEXs, lending protocols)             |
| `NFT`          | Non-Fungible Token platforms (e.g., marketplaces, galleries)                |
| `GameFi`       | Blockchain-based games and play-to-earn platforms                           |
| `Governance`   | Decentralized Autonomous Organizations                                      |
| `Social`       | Social platforms or media (e.g., Twitter/Facebook clones)                   |
| `Art`          | Art-related platforms (e.g., digital art galleries)                         |
| `Tool`         | General-purpose tools (e.g., wallets, explorers, or utilities)              |
| `E-Commerce`   | Platforms for decentralized online shopping                                 |
| `Infrastructure`| Blockchain infrastructure (e.g., nodes, APIs, oracles)                     |
| `Education`    | Platforms for blockchain/web3 education                                     |
| `Media`        | News, blogs, and content platforms related to web3                          |
| `Protocol`     | Blockchain or layer-specific protocols                                      |
| `Aggregator`   | Aggregators (e.g., price tracking, DeFi aggregators)                        |
| `Marketplace`  | General marketplaces (not specific to NFTs)                                 |
| `Analytics`    | Tools for blockchain data analysis or visualization                         |
| `Community`    | Community-oriented platforms (forums, chat rooms, etc.)                     |
| `Identity`     | Platforms for decentralized identity and verification                       |
| `Other`        | Catch-all for platforms that don't fit into the above                       |

Make sure to include at least one of these categories in your website file.

## Accessing the Full List of Websites
Developers can access the full list of websites using the raw file available at the following URL:

https://github.com/massalabs/Deweb-Providers/raw/refs/heads/main/websites.yaml
