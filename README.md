# MCP Server Project

This project consists of a client-server architecture with separate components for the server and client applications.

## Project Structure

```
mcp-server/
├── client/     # Client application
├── server/     # Server application
└── .gitignore  # Git ignore configuration
```

## Getting Started

### Prerequisites

- Node.js (version 14 or higher recommended)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd mcp-server
```

2. Install server dependencies:
```bash
cd server
npm install
```

3. Install client dependencies:
```bash
cd ../client
npm install
```

### Running the Application

1. Start the server:
```bash
cd server
npm start
```

2. Start the client:
```bash
cd client
npm start
```

## Development

- The server application is located in the `server/` directory
- The client application is located in the `client/` directory

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 