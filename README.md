# DecentralizedAuthenticator

![License](https://img.shields.io/badge/license-MIT-green) ![Build](https://img.shields.io/badge/build-passing-brightgreen) ![Coverage](https://img.shields.io/badge/coverage-100%25-brightgreen)

## Introduction
This project introduces a blockchain-based identity management system that provides a decentralized method for managing digital identities securely and efficiently. Leveraging blockchain technology, this system ensures that personal identity information remains under the user's control, mitigating the risks associated with centralized databases.

## Technologies
- **Ethereum**: Implements smart contracts for secure transactions and automated enforcement of agreements.
- **Smart Contracts**: Written in Solidity, these contracts automate and enforce the terms of identity verification and document transactions.
- **Metamask**: A crypto wallet used to manage and authenticate digital identities on the Ethereum blockchain.
- **IPFS**: Utilizes the InterPlanetary File System for decentralized file storage, enhancing privacy and data accessibility.
- **Ganache**: Generates sample blockchain networks for testing, allowing transactions with Ethereum in a controlled environment.

## System Architecture 🏛️

Below is a diagram illustrating the overall architecture of the Decentralized Authenticator system:

![System Architecture Diagram]([link-to-diagram-image](https://github.com/mandarc64/DecentralizedAuthenticator/blob/main/projimage.png))

1. **User Registration**: Users and organizations register by providing an email address. Upon verification, they are prompted to create a secure password.
2. **Document Management**: Users can upload and categorize their identity documents on the platform. These documents are stored as cryptographic hashes on IPFS and their references are stored on the blockchain.
3. **Access Control**: Organizations request access to user documents through blockchain transactions. Users grant or deny access based on the transaction requests.
4. **Data Immutability**: Utilizing blockchain's inherent features, the system ensures that once data is recorded, it cannot be altered or deleted. This guarantees the integrity of the identity data.

## Features
- **Decentralized Storage**: Eliminates centralized points of failure and reduces privacy risks by distributing data across the network.
- **Enhanced Security**: With blockchain and IPFS, data is encrypted and fragmented, reducing the potential for unauthorized access.
- **Data Segregation and Access**: Organizations have access only to the specific documents they are permitted to see, as agreed upon by the user.

## Usage
This section should detail how to navigate the system, manage identity documents, and handle access requests. Include code snippets and command examples where applicable.

## Contributing
Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests to us.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Future Work
Plans for future enhancements include conducting large-scale, real-time experiments using real data on the public Ethereum network to improve and expand the functionality of the system.
