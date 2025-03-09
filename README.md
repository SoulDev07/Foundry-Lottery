# Foundry Lottery 🎰

A decentralized and transparent lottery system built with Solidity and Foundry.

## Overview

This project implements a trustless lottery system on the blockchain where:
- Players can enter by paying a ticket fee
- A verifiably random winner is selected
- The winner receives the entire prize pool

## Getting Started

### Prerequisites

- [Foundry](https://book.getfoundry.sh/getting-started/installation)

### Installation

1. Clone the repository
```bash
git clone https://github.com/SoulDev07/foundry-lottery
cd foundry-lottery
```

2. Install dependencies
```bash
make install
```

3. Build the project
```bash
forge build
```

## Usage

Deploy the contract
```bash
forge script script/DeployRaffle.s.sol
```

## Testing

Run the full test suite:
```bash
forge test
```

For more verbose output with traces:
```bash
forge test -vv  # Logs emitted during tests
forge test -vvv # Stack traces for failures
forge test -vvvv # Full stack traces and setup details
```

Run specific tests by matching the test name:
```bash
forge test --match-test testFunctionName
```

Generate a test coverage report:
```bash
forge coverage
forge coverage --report debug # Generate debug report
```

Run tests with gas reporting:
```bash
forge test --gas-report
```
