# 🚀 100 Days of Consistent Commits

This repository is my commitment to showing up every single day and building in public.

For the next 100 days, I will push at least one meaningful commit daily — no excuses.

---

## 🎯 Goal

To improve my skills through consistency, discipline, and real execution.

This is not about perfection — it’s about progress.

---

## 📌 What You’ll Find Here

- 🧠 Problem solving (algorithms, logic building)
- ⚙️ Mini projects & scripts
- 🌐 Web3 / DeFi experiments
- 📒 Notes & learnings
- 🛠 Real-world coding practice

---

## 🗂 Structure

Each day has its own folder:

---

## 📜 Rules

- ✅ At least 1 meaningful commit per day
- ❌ No empty or spam commits
- ✅ Document what I learn
- ✅ Stay consistent for 100 days

---

## 📈 Progress Tracker

| Day | Status |
|-----|--------|
| Day 1 | ✅ |
| Day 2 | ✅ |
| Day 3 | ⏳ |
| ... | ... |

---

## 💭 Why This Matters

Consistency beats motivation.

By committing daily, I’m building:
- Discipline
- Real skills
- A public proof of work

---

## 🔗 Let’s Connect

If you're on a similar journey, feel free to fork, follow, or contribute.

Let’s grow together 🚀
# 🚀 100 Days of Consistent Commits

This repository tracks my journey of building and learning every single day.

Each day = one meaningful commit.

---

## 🎯 Goal

To build real skills through daily execution:

* Coding
* Problem solving
* Web3 exploration
* Documentation

---

## 📅 Daily Breakdown

### ✅ Day 1 — Setup

* Initialized repository
* Created README
* Defined structure and rules

---

### ✅ Day 2 — Simple Script

* Built a basic script (JavaScript/Python)
* Focus: logic + clean code

---

### ✅ Day 3 — Algorithm Practice

* Solved 1 problem
* Focus: thinking + problem-solving approach

---

### ✅ Day 4 — Web3 Test

* Tested wallet connection (ethers.js / web3.js)
* Interacted with blockchain basics

---

### ✅ Day 5 — DeFi Notes

* Wrote notes on APY, yield, and risk
* Broke down key DeFi concepts

---

## 📂 Structure

day-01/ → Setup
day-02/ → Script
day-03/ → Algorithm
day-04/ → Web3
day-05/ → DeFi Notes

---

## 📜 Rules

* 1 meaningful commit daily
* No empty commits
* Focus on learning + building
* Stay consistent

---

## 📈 Progress

| Day | Task       | Status |
| --- | ---------- | ------ |
| 1   | Setup      | ✅      |
| 2   | Script     | ✅      |
| 3   | Algorithm  | ✅      |
| 4   | Web3       | ✅      |
| 5   | DeFi Notes | ✅      |

---

## 💭 Mindset

This is proof of work.

No noise. Just consistency.
init repo + add README with 100 days plan
add simple script for basic logic practice
solve algorithm problem and document approach
test wallet connection using ethers.js
add notes on DeFi APY, yield, and risks
// Simple calculator

function calculate(a, b, operator) {
  if (operator === "+") return a + b;
  if (operator === "-") return a - b;
  if (operator === "*") return a * b;
  if (operator === "/") return a / b;
}

console.log(calculate(10, 5, "+")); // 15
// Factorial of a number

function factorial(n) {
  if (n === 0) return 1;
  return n * factorial(n - 1);
}

console.log(factorial(5)); // 120
// Factorial of a number

function factorial(n) {
  if (n === 0) return 1;
  return n * factorial(n - 1);
}

console.log(factorial(5)); // 120
# Day 8 - Blockchain Basics

- Blockchain is a distributed ledger
- Transactions are grouped in blocks
- Blocks are linked via cryptography
- Decentralization reduces single points of failure
- Public vs private blockchains
// Generate a random number between min and max

function random(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}

console.log(random(1, 100));
// Bubble sort example

function bubbleSort(arr) {
  for(let i = 0; i < arr.length; i++) {
    for(let j = 0; j < arr.length - i -1; j++) {
      if(arr[j] > arr[j+1]) {
        [arr[j], arr[j+1]] = [arr[j+1], arr[j]];
      }
    }
  }
  return arr;
}

console.log(bubbleSort([5, 2, 9, 1, 5]));
# Day 11 - Wallets & Keys

- Wallet stores private/public keys
- Private key: do NOT share
- Public key: can receive funds
- Hot wallet: online, easy access, higher risk
- Cold wallet: offline, safer
// Check if number is even or odd

function checkNumber(num) {
  return num % 2 === 0 ? "Even" : "Odd";
}

console.log(checkNumber(7)); // Odd
// Print first n Fibonacci numbers

function fibonacci(n) {
  const seq = [0, 1];
  for(let i = 2; i < n; i++) {
    seq.push(seq[i-1] + seq[i-2]);
  }
  return seq;
}

console.log(fibonacci(10));
# Day 14 - Smart Contracts

- Self-executing contracts on blockchain
- Written in Solidity (Ethereum)
- Automate trustless agreements
- Examples: token, NFT, DeFi protocols
