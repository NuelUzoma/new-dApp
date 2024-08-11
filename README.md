# String Uppercase Converter dApp

This is a decentralized application (dApp) built on the Cartesi platform that converts strings from their hexadecimal representation to uppercase. The dApp also tracks users who submit strings and counts the total number of successful conversions.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
  - [Running the dApp](#running-the-dapp)
  - [Sending Inputs](#sending-inputs)
  - [Inspecting Data](#inspecting-data)
- [Cartesi Commands](#cartesi-commands)
- [Contributing](#contributing)

## Introduction

This dApp converts hexadecimal strings to uppercase and keeps track of users and successful conversions. It uses Cartesi’s off-chain computation capabilities to process requests efficiently.

## Features

- Converts hexadecimal strings to their uppercase equivalents.
- Tracks users who submit strings for conversion.
- Counts the total number of successful conversions.
- Handles simple routing to provide user and transaction data.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/en/) installed on your machine.
- Docker installed for running Cartesi services.
- [Cartesi](https://docs.cartesi.io/cartesi-machine/) installed and configured.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/string-uppercase-dapp.git
    cd string-uppercase-dapp
    ```

2. Build the dApp using Cartesi:
    ```bash
    cartesi build
    ```

## Usage

### Running the dApp

1. Start the Cartesi machine:
    ```bash
    cartesi run
    ```

### Sending Inputs

1. To convert a hexadecimal string to uppercase, send the input string to the Cartesi machine using:
    ```bash
    cartesi send
    ```

2. The machine will process the string and return its uppercase version. If the string is not in hexadecimal format, the request will be rejected.

### Inspecting Data

1. You can inspect the list of users who have submitted requests:
    ```bash
    cartesi send
    ```

2. You can also check the total number of successful conversions:
    ```bash
    cartesi send
    ```

## Cartesi Commands

- **cartesi doctor**: Check if your Cartesi environment is properly set up.
    ```bash
    cartesi doctor
    ```

- **cartesi build**: Build the Cartesi machine and prepare the dApp for execution.
    ```bash
    cartesi build
    ```

- **cartesi run**: Run the Cartesi machine, which executes the dApp.
    ```bash
    cartesi run
    ```

- **cartesi send**: Send data (like strings) to the Cartesi machine for processing.
    ```bash
    cartesi send
    ```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request if you have any improvements or bug fixes.
