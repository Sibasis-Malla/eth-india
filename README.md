<!-- [![All Contributors](https://img.shields.io/github/all-contributors/sambit-sankalp/project-phoenixfi?color=ee8449&style=flat-square)](#contributors) -->
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<!-- Other badges-->


![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white)
![Web3js](https://img.shields.io/badge/web3.js-F16822?style=for-the-badge&logo=web3.js&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-e6e6e6?style=for-the-badge&logo=solidity&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

<!-- Other badges-->

<br />
<p align="center">
    <img src="https://res.cloudinary.com/amznpersonal1/image/upload/v1703009365/wycfc6lbtnqp1ih3hrvd.png" alt="Logo" width="80">
  </a>

  <h3 align="center">PhoenixFi</h3>

  <p align="center">
    The official repository for the website of Phoenixfi
    <br />
    <a href="https://phoneixfi.vercel.app/">View Live</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
      </ul>
        <li><a href="#built-with">Built With</a></li>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#running-the-project">Running the project</a></li>
      </ul>
    </li>
    <li><a href="#features">Features</a></li>
    <li><a href="#block-diagram">Block Diagram</a></li>
    <li><a href="#screenshots">Screenshots</a></li>
      <li><a href="#repositories">Repositories</a></li>
    <!-- <li><a href="#contributors">Contributors</a></li> -->
  </ol>
</details>

## About The Project

PhoenixFi revolutionizes the FileCoin ecosystem by enabling Storage Providers to overcome funding gaps through innovative lending solutions. The platform employs robust risk mitigation strategies, ensuring staking remains lucrative while minimizing defaults. An incentivization model rewards both stakers and providers, adding tangible value to the FileCoin Network. Challenges include developing accurate ML models for reputation prediction and collateral demand, designing a balanced reward system, and implementing effective measures to prevent loan defaults. PhoenixFi pioneers a transformative approach, fostering a dynamic and sustainable FileCoin ecosystem.

## Built With

Following technologies and libraries are used for the development of this website

- [React](https://reactjs.org/)
- [IPFS](https://ipfs.io/)
- [React Router](https://reactrouter.com/)
- [Solidity](https://docs.soliditylang.org/)
- [Filecoin](https://filecoin.io/)
- [Ethereum](https://ethereum.org/en/)
- [Web3.js](https://web3js.readthedocs.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Python](https://www.python.org/)
- [Vercel](https://vercel.com/)

## Getting Started

To setup the project locally the steps below.

### Prerequisites

- Please make sure you have [metamask](https://metamask.io/) installed and connected to Filecoin's Calibration testnet and have some test matic in your wallet

- [Node.js](https://nodejs.org/en/download/)

```sh
  # Homebrew
  brew install nodejs

  # Sudo apt
  sudo apt install nodejs

  # Packman
  pacman -S nodejs

  # Module Install
  dnf module install nodejs:<stream> # stream is the version

  # Windows (chocolaty)
  cinst nodejs.install

```

- [Git](https://git-scm.com/downloads)

```sh
  # Homebrew
  brew install git

  # Sudo apt
  apt-get install git

  # Packman
  pacman -S git

  # Module Install (Fedora)
  dnf install git

```

### Running the project.

The project uses NPM. It is strictly advised to stick with NPM so as to avoid dependency conflicts down the line.

```
## Checkout into the project client directory
cd client

## Install Dependencies
npm install

## Run the Project
npm start

```

Following are the commands to remove/add new dependencies using yarn

```
## Add a new Package
npm install <package-name>

## Remove an existing Package
npm uninstall <package-name>

## Save Package as a Dev Dependency
npm install <package-name> --save-dev
```
## Repositories for Lilypad Job

- [Shell Script to run Lilypad](https://github.com/sambit-sankalp/lilypadscript)
- [Lilypad Docker Configuration](https://github.com/sambit-sankalp/lilyconfig)


## Features

### Staking Liquidity Solutions:

PhoenixFi empowers Storage Providers (SPs) by offering loans to cover insufficient funds for FileCoin staking, attracting more participants and optimizing infrastructure utilization.

### Robust Risk Mitigation:

The platform implements stringent eligibility checks and feasible loan amount determinations to mitigate risks associated with lending, safeguarding SPs' on-chain reputation and minimizing potential losses.

###  Incentivization Model:

PhoenixFi introduces a unique model that rewards both stakers and SPs, providing tangible monetary gains and showcasing the real-world value of active participation in the FileCoin Network.

### Predictive ML Models:

The project leverages advanced machine learning models to accurately predict reputation and collateral demand, ensuring a reliable and effective lending ecosystem.

### Balanced Reward Generation:

Designing a reward system that benefits both stakers and storage providers, PhoenixFi creates a fair and mutually beneficial environment, encouraging sustained engagement in the FileCoin ecosystem.

### Loan Default Prevention:

Implementing checks and balances, such as a beneficiary system, the platform actively prevents loan defaults, enhancing the overall stability and reliability of the lending platform.

## Block Diagram

<img src="https://res.cloudinary.com/sambitsankalp/image/upload/v1702274034/architecture_qdhwzj.png" alt="Block Diagram" width="100%">

## Screenshots

<img src="https://res.cloudinary.com/sambitsankalp/image/upload/v1702274331/image1_nxv1ap.png" alt="Logo" width="100%">
<img src="https://res.cloudinary.com/sambitsankalp/image/upload/v1702274328/image2_ahm19s.png" alt="Logo" width="100%">


<!-- ## Contributors -->

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
