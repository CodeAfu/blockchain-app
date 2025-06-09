## Structure

- `/blockchain-frontend` - Next.js frontend (with server actions for backend)
- `/smart_contract` - Solidity smart contracts

## Setup

1. Clone the repository with submodules:

```bash
git clone --recursive https://github.com/CodeAfu/blockchain-app.git

# Use if you missed --recursive on clone
git submodule update --init --recursive
```

2. Follow setup instructions in each subdirectory's README.md

## Commands

```bash
# Updates
git submodule update --remote --merge
git config -f .gitmodules submodule.blockchain-frontend.branch main
git config -f .gitmodules submodule.smart_contract.branch master
```
