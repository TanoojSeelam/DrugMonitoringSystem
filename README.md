# 🏥 Drug Monitoring System

Welcome to the Drug Monitoring System repository! This project is aimed at providing a system for monitoring drugs in a healthcare environment.

## 🚀 Features

Explore the following features showcased in this project:

- **Drug Database**: Maintain a database of drugs including their details such as name, dosage, expiry date, etc.
- **Monitoring**: Monitor drug usage, stock levels, and expiry dates to ensure efficient management and timely replenishment.
- **Alerts and Notifications**: Receive alerts and notifications for low stock levels, expired drugs, etc.
- **User Management**: Manage user accounts with different roles and permissions for accessing and updating drug information.

## 📁 Project Structure

The project structure is organized as follows:

- `backend/`: Contains the backend code for the Drug Monitoring System.
- `frontend/`: Contains the frontend code for the Drug Monitoring System.
- `database/`: Contains database scripts and configurations.

## 🛠️ Requirements

Before running the project, ensure you have the following prerequisites:

- **Backend Requirements**:
  - **Programming Language**: Python
  - **Framework**: Django
  - **Database**: SQLite, PostgreSQL (optional)
- **Frontend Requirements**:
  - **JavaScript Framework**: React.js
- **Database Requirements**: SQLite or PostgreSQL
- **Development Environment**: Any text editor, Git

## 🚦 Getting Started

Follow these steps to get started with the project:

1. Clone this repository to your local machine.
2. Set up the backend by navigating to the `backend/` directory and following the instructions in the README file.
3. Set up the frontend by navigating to the `frontend/` directory and following the instructions in the README file.
4. Set up the database by executing the database scripts located in the `database/` directory.
5. Run the backend server.
6. Run the frontend server.
7. Access the Drug Monitoring System through your web browser.

## 🛠️ Tech Stack

- **Blockchain**: Ethereum
- **Smart Contract Language**: Solidity
- **Frontend**: React.js
- **Blockchain Interaction Library**: Ethers.js

## 🏃‍♂️ How to Run

### Compiling and Deploying the Smart Contract

1. Open the `supplychain.sol` file in Remix IDE.
2. Compile the smart contract in Remix IDE.
3. Deploy the compiled contract in the Remix IDE environment using Metamask.
4. Once deployed, obtain the contract address from the deployed instance.

### 💻🖥Frontend Setup

1. Navigate to the `client/` folder.
2. Run `npm install` to install dependencies.
3. Go to the `components/` folder and locate four files.
4. In each file, locate the line `const ContractAddress = '<your_contract_address>'` and replace `<your_contract_address>` with the contract address obtained from Remix IDE.
5. Run `npm start` to start the frontend server.
6. Access the application through your web browser at `http://localhost:3000`.

## 🚀 Usage

After setting up the frontend and connecting it to the deployed smart contract, you can use the UI provided to interact with the contract. You can perform transactions such as saving drug status, setting products, workers, or other data related to the monitoring system.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
