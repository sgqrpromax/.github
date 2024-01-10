# SGQR Pro Max

**SGQR DeFi Payment System, using Singapore's Standardised E-Payment QR Codes, powered by XRP Ledger && XRP Ledger EVM Side Chain**

<div align="center">
<img 
  src="https://github.com/sgqrpromax/.github/blob/main/assets/logo-grey.png" 
  style="width:40% ; height:40%;"
/>
</div>

## 📝 Report

[SGQR Pro Max Report](https://docs.google.com/document/d/1gl4Az8Ru_RCtfZpL4rT_4Ridk-icp56TpXDgvwWStM0)

## 🕧 Introduction

SGQR is the world’s first unified payment QR code system. It combines multiple payment QR codes into a single SGQR label, making QR payments in Singapore simple for both consumers and merchants.

With cryptocurrency gaining popularity, and Ripple securing a Singapore payments license in 2023, cryptocurrency as a mode of payment in the world becomes an inevitable future. That's where **SGQR Pro Max** swings in!

SGQR Pro Max leverages **SGQR's unified payment QR Code** and **XRP Ledger** to provide a **DeFi payments alternative**.

Anyone owning a mobile phone with a **camera**, **data connectivity**, and an **EVM Wallet** will be able to make payments via SGQR Pro Max so long as the merchant supports their choice of payment.

**Visit <a href="https://sgqrpromax.github.io/SGQR-Pro-Max/">SGQR Pro Max</a> at the Deployed Website**

### 🙋🏻 How it works

1. Connect your wallet to SGQR Pro Max.
2. Scan a Merchant SGQR Code.
3. Enter the amount of SGDk.
4. Click on "Send Tokens".
5. Voila! It's done. You have paid a merchant in crypto!

<div align="center">
<img 
  src="https://github.com/sgqrpromax/.github/blob/main/assets/sgqrpromax-flow.jpg"
/>
</div>

## ✨ Features

1. 😌 **Pre-onboarded Users**: Users can scan easily existing SGQR Codes and make payments in cryptocurrency.

2. 🏘️ **Ease of Use**: Anyone owning a mobile phone with a camera, data connectivity, and an EVM Wallet will be able to make payments

3. 🪫 **Low Fees**: XRP Ledger lowers the associated fees exponentially for both the merchant and the user.

4. 🆙 **100% Uptime**: XRP Ledger provides a reliable blockchain infrastructure that ensures undisrupted payments.

5. 🟰 **Standardisation**: SGQR being the world’s first unified payment QR code, combines multiple payment schemes into a single SGQR Code.

## 🗺️ Architecture

<div align="center">
<img 
  src="https://github.com/sgqrpromax/.github/blob/main/assets/sgqrpromax-token-bridge.jpg"
    style="width:75% ; height:75%;"
/>
</div>
<br />
<div align="center">
<img 
  src="https://github.com/sgqrpromax/.github/blob/main/assets/sgqrpromax-architecture.jpg"
/>
</div>

## 🌐 Software

- **XRP Ledger**: We use XRPL main chain to swap stablecoins for SGDk. The SGDk will then be bridged to the EVM side chain. The reason for using the main chain for holding and swapping for SGDk is explained as follows.
- **EVM Side Chain**: We used the EVM side chain to hold all the smart contract backend, enabling payment processing for everyone in Singapore.
- **Tech Stack**: React, JavaScript, HTML, CSS, Foundry, Solidity, Python.

## ⌚️ Timeline

<div align="center">
<img 
  src="https://github.com/sgqrpromax/.github/blob/main/assets/sgqrpromax-timeline.jpg"
/>
</div>

## 🔧 Contributing

We welcome any feedback, improvements, and amendments to these repositories 🙌 :

- [Frontend](https://github.com/sgqrpromax/SGQR-Pro-Max) - A React Frontend to tie the whole project together.
- [Backend](https://github.com/sgqrpromax/sgqrpromax-smart-contracts) - A lightweight Foundry library containing SGQR Pro Max smart contracts.
