# Blockchain Batch Payment with Blacklisting

A decentralized batch payment application that leverages blockchain technology to process payments in bulk. The system includes a blacklist mechanism based on user reports via EmailJS—ensuring that blacklisted accounts are prevented from using the application.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Dependencies](#project-dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a blockchain-based batch payment solution that enables users to process multiple transactions at once while ensuring security through a user-report-driven blacklisting mechanism. Email reports received via EmailJS flag any account as blacklisted, thereby preventing access to the application.

## Features

- **Batch Payment Processing:** Efficiently process multiple payments in a single blockchain transaction.
- **Blacklist Mechanism:** Restrict access for blacklisted accounts based on user reports collected via EmailJS.
- **Decentralized & Secure:** All payments are processed on-chain with smart contracts for transparency and security.
- **Modern Frontend:** A user-friendly interface built with React.js and Next.js.
- **Blockchain Integration:** Smart contracts developed using Solidity and Foundry.
- **MetaMask Support:** Secure wallet integration via MetaMask for user authentication and transaction signing.

## Tech Stack

- **Frontend:** React.js, Next.js
- **Blockchain & Smart Contracts:** Solidity, Foundry
- **Wallet Integration:** MetaMask
- **Email Service:** EmailJS (for handling user reports and blacklist notifications)
- **Documentation of Dependencies:** See the [requirements.txt](requirements.txt) file

## Architecture

1. **Frontend Application:**  
   Developed using React.js and Next.js, the frontend offers a responsive user interface for managing batch payments and account statuses. MetaMask integration facilitates secure blockchain interactions.

2. **Smart Contracts:**  
   Written in Solidity and built with Foundry, the smart contracts encapsulate all batch payment logic and enforce blacklist restrictions on-chain.

3. **Blacklist Mechanism:**  
   Users can report suspicious activities via a form integrated with EmailJS. These reports are used to update a blacklist, ensuring that flagged accounts are barred from accessing the payment system.

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
