# 🎡 SpinTheWheel – Simple Solidity Random Number Game

A fun and beginner-friendly Ethereum smart contract that simulates spinning a wheel to get a random number between **1 and 10**.  
This project is perfect for learning how randomness, hashing, and state variables work in Solidity.

---

## 🚀 Project Description

SpinTheWheel is a lightweight smart contract written in Solidity that allows any user to call a function named `spin()` and receive a pseudo-random wheel result.  
The number gets stored on-chain, making every spin publicly visible and verifiable.

This is **NOT** meant for production randomness or gambling use cases, but it’s great for:
- Learning Solidity  
- Understanding state updates  
- Experimenting with pseudo-randomness  
- Demonstrating contract interactions  

---

## 🎯 What It Does

- Generates a pseudo-random number between **1 and 10**
- Stores the result in a public variable `lastSpin`
- Lets anyone trigger a wheel spin by calling `spin()`
- Uses Solidity hashing (`keccak256`) for randomness (educational, not secure)

---

## ✨ Features

- ✔️ Simple & beginner-friendly  
- ✔️ Fully on-chain state storage  
- ✔️ Public variable for transparency  
- ✔️ Minimalistic logic (easy to understand)  
- ✔️ Clean and readable code  

---

## 🔗 Deployed Smart Contract

**Contract Address:**  
`0x91411e078028a4148c40d51acbfe26befcb676f37086c7dc2423e2cb8a490c95`

You can view it on your preferred blockchain explorer by pasting the above address.

---


