<p align="center">
  <img src="./docs/logo/logo-white-center.svg" alt="State Space Logo" width="700"/>
</p>

<p align="center">  
    <a href="https://state.space"><img src="https://img.shields.io/badge/Platform-Web-blue)" alt="State Space"></a>
    <a href="https://state.space"><img src="https://img.shields.io/badge/EVM-Compatible-brightgreen)" alt="State Space"></a>
    <a href="https://state.space"><img src="https://img.shields.io/badge/Docs-Available-orange" alt="State Space"></a>

</p>


<p>
    State Space is a visual formal verification solution for Ethereum-compatible (EVM) smart contracts, providing formally derived test case generation, advanced security analysis, and code behavior validation. 
</p>


<p align="center">
  <img src="./docs/media/images/Workbench.png" alt="State Space Workbench" width="700">
</p>

## Table of Contents

- [What is State Space?](#what-is-state-space)
- [Key Features](#key-features)
- [Benefits](#benefits)
- [Supported Frameworks](#supported-frameworks)
- [Getting Started](#getting-started)
- [Try it Out](#try-it-out)
- [Documentation](#documentation)
- [Resources](#resources)
- [System Requirements](#system-requirements)
- [Licensing](#licensing)
- [Contact](#contact)

## What is State Space?

State Space leverages dynamic symbolic execution and a fully defined EVM semantics model to automatically generate and visualize the complete state space of multi-contract protocols. Rather than proving absence of bugs, it systematically:

- **Discovers all feasible execution paths** by solving path constraints with SMT solvers
- **Generates concrete input values** that trigger each unique execution path
- **Visually maps the entire behavior space** of your smart contracts
- **Surfaces both expected behaviors and edge cases** that traditional testing often misses
- **Leverages fully defined EVM semantics** for deep path and edge case discovery, simulating on-chain execution without needing to modify your code. 

Unlike manual testing where engineers create specific test cases, State Space automatically explores your contract's behavior space, creating a comprehensive visual representation that allows security engineers to inspect actual contract behavior under all possible inputs and conditions.

## Key Features

- **Visual Formal Testing**: Design formal analysis testing flows using a visual canvas (symbolic execution). 
- **Input Parameterization**: Search the state space using both concrete and symbolic input values for wide or targeted test case generation.
- **Autonomous Path Exploration**: Systematically discover all feasible execution paths, deep edge cases, and the inputs that trigger them with no upfront manual effort. 
- **Foundry/Hardhat Test Suite Generation**: Export comprehensive, reproducible Foundry and Hardhat test suites to cover all edge cases. Get to 100% coverage using formal methods, not AI. 
- **State Analysis & Validation**: Human readable visual format to validate exact code behavior via decoded and raw storage values, state changes, account values and more. 
- **Collaboration**: Invite team members or auditors to participate in formal validation and testing workflows. 

## Benefits

- Uncover edge cases that manual testing misses
- Validate smart contract behavior with mathematical precision
- Save weeks/months of engineering effort
- Increase code quality and security
- Accelerate time-to-market
- Prepare for audits to maximize engagement value
- Get immediate feedback on bugs or unintended functionality
- Standardize security/quality across teams with varying experience and skillsets

## Supported Frameworks

State Space works seamlessly with the most popular Ethereum development frameworks:

- **Foundry** - Complete integration with Forge testing and deployment scripts
- **Hardhat** - Full support including Ignition deployment modules

## Getting Started

### Install the CLI

```bash
brew install state-space/state-space/cli
```

### Initialize Your Project

```bash
state-space init
```

### Configure and Deploy

Update your `state-space.toml` configuration file and deploy to State Space:

```bash
state-space push
```

### Start Using Workbench

Log in to the [State Space Workbench](https://state.space/me) to begin designing test scenarios for your smart contracts.

## Try it Out

Want to see State Space in action? You can:

- [Sign up for an account](https://app.state.space/sign-up)
- Try our [ERC20 playground](https://state.space/me) with pre-loaded examples
- Follow our quick tutorial to [validate ERC20 Pausable feature](https://docs.state.space/tutorials/erc20-pause-mint)

## Documentation

For more detailed information, check out our tutorials:
- [ERC20: Pause->Mint Tutorial](https://docs.state.space/tutorials/erc20-pause-mint)
- [ERC20: End-to-End Testing of transferFrom](https://docs.state.space/tutorials/erc20-transferfrom)

## Resources

- [State Space Example Projects](https://github.com/state-space/state-space/examples)
- [Documentation](https://docs.state.space)

## System Requirements

State Space is a cloud-based platform with the following requirements:
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Command-line interface for the CLI tools using
- CLI Compatible with macOS or Linux via `brew`

## Licensing

State Space is a commercial product. Please [contact us](mailto:contact@state.space) for licensing options and pricing information.

## Contact

For questions or support, contact us at [contact@state.space](mailto:contact@state.space).
