# Uniswap V2 (CoolSwap-interface) Fork

Welcome to the Uniswap V2 ( CoolSwap-interface ) fork project! This is a customized version of Uniswap V2, designed to suit specific requirements or enhancements. Below you will find the necessary steps to set up and run the project.

## Prerequisites

- Node.js =v16
- npm (Node Package Manager)

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/zOthix/uniswap-lumio.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd uniswap-lumio
   ```
3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Set env variables**
   ```bash
   cp .env.example .env
   ```

   Fill the environment variables
   
   ```bash
   # rpc url
   REACT_APP_NETWORK_URL=

   # chain id
   REACT_APP_CHAIN_ID=

   # wallet connect project id
   # https://cloud.walletconnect.com/
   REACT_APP_WALLET_CONNECT_PROJECT_ID=

   # block explorer url
   REACT_APP_EXPLORER_URL=

   GENERATE_SOURCEMAP=false
   NODE_ENV=development
   ```


## Running the Application

```bash
npm run start
````

This command will initiate the Uniswap V2 fork and start the application. Once the application is up and running, you can access the application via the specified endpoint (e.g., http://localhost:3000).
