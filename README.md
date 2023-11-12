# NodeCrypt - Backend for File Sharing Site

For more detailed information, refer to the [Notion page](https://deadgawk.notion.site/NodeCrypt-Backend-for-File-Sharing-Site-a4c7c2f271e54173995d3775b166973a?pvs=4).

## Introduction

This project focuses on developing the backend for a file-sharing site, continuing the work on the 'File System Encryption using AES-256 over HTTPS' project.

The HTTPS setup is an integral part of the project, involving the configuration of a custom domain with a free and custom Top-Level Domain (TLD). The SSL certificate has been enabled to ensure secure HTTPS connections. The hosting is done on [InfinityFree](https://www.infinityfree.com/), a free web hosting platform that simplifies website development at no cost.

Before diving into the documentation, the domain for this project is [datavault.rf.gd](https://datavault.rf.gd).


## Getting Started

### Installation

To install project dependencies, run:

```bash
npm install
```

### Configuration

Create a .env file in the project root and add the following configurations:

```bash
PORT=3000
MONGODB_URI=mongodb://localhost:3000/fileSharing
```

### Start the Server

To start the server in development mode, run:

```bash
npm run devStart
```

### Project Domain

Visit datavault.rf.gd to explore the live project.

## Contributing

If you'd like to contribute to the project, please follow our contribution guidelines.

## License

This project is licensed under the [MIT License](https://github.com/Gaoh19/NodeCrypt/blob/4b60013a209ac983e495247140cbbac9956893bf/LICENSE)

This project draws inspiration from [WebDevSimplified](https://github.com/WebDevSimplified/file-sharing-node-js.git).

