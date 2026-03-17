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
// Read a file (Node.js example)

const fs = require('fs');

fs.readFile('example.txt', 'utf8', (err, data) => {
  if(err) throw err;
  console.log(data);
});
// Reverse a string

function reverseString(str) {
  return str.split("").reverse().join("");
}

console.log(reverseString("hello")); // olleh
# Day 17 - Gas Fees

- Gas is the cost to execute operations on Ethereum
- Paid in ETH
- Complex transactions = higher gas
- Layer 2 reduces gas fees
// Fetch data from an API

const fetch = require('node-fetch');

async function getData(url) {
  const response = await fetch(url);
  const data = await response.json();
  console.log(data);
}

getData('https://api.coindesk.com/v1/bpi/currentprice.json');
// Find max and min in array

function findMaxMin(arr) {
  return { max: Math.max(...arr), min: Math.min(...arr) };
}

console.log(findMaxMin([5, 3, 9, 1, 7]));
# Day 20 - DEX vs CEX

- CEX: Centralized Exchange (Binance, Coinbase)
  - Pros: High liquidity, fast
  - Cons: Custodial, trust needed
- DEX: Decentralized Exchange (Uniswap, Sushiswap)
  - Pros: Non-custodial, privacy
  - Cons: Slippage, lower liquidity
// Simple CLI tool to greet user

const readline = require('readline').createInterface({
  input: process.stdin,
  output: process.stdout
});

readline.question('Enter your name: ', name => {
  console.log(`Hello, ${name}!`);
  readline.close();
});
// Binary search in sorted array

function binarySearch(arr, target) {
  let left = 0, right = arr.length - 1;
  while (left <= right) {
    const mid = Math.floor((left + right) / 2);
    if (arr[mid] === target) return mid;
    if (arr[mid] < target) left = mid + 1;
    else right = mid - 1;
  }
  return -1;
}

console.log(binarySearch([1,3,5,7,9], 5)); // 2
# Day 23 - Liquidity Pools

- Users provide tokens to pool
- Pools enable trades in DEX
- Earn fees proportional to contribution
- Risk: impermanent loss
// Simple random password generator

function generatePassword(length = 8) {
  const chars = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789!@#$%^&*';
  let password = '';
  for(let i = 0; i < length; i++) {
    password += chars.charAt(Math.floor(Math.random() * chars.length));
  }
  return password;
}

console.log(generatePassword(12));
// Check if a number is prime

function isPrime(num) {
  if(num < 2) return false;
  for(let i = 2; i <= Math.sqrt(num); i++) {
    if(num % i === 0) return false;
  }
  return true;
}

console.log(isPrime(17)); // true
# Day 26 - Staking

- Lock tokens in protocol to earn rewards
- Provides network security
- Risks: token lockup, smart contract bugs
// Basic todo list in memory

let todos = [];

function addTodo(item) {
  todos.push(item);
}

function listTodos() {
  console.log(todos);
}

addTodo("Learn GitHub");
addTodo("Write script");
listTodos();
// Rotate array by k positions

function rotateArray(arr, k) {
  k %= arr.length;
  return arr.slice(-k).concat(arr.slice(0, arr.length - k));
}

console.log(rotateArray([1,2,3,4,5], 2)); // [4,5,1,2,3]
# Day 29 - Yield Farming

- Provide liquidity to earn rewards
- High APY = high risk
- Monitor impermanent loss
- Check smart contract security
// Parse CSV string to array

function parseCSV(str) {
  return str.split("\n").map(line => line.split(","));
}

const csv = "name,age\nAlice,25\nBob,30";
console.log(parseCSV(csv));
// Parse CSV string to array

function parseCSV(str) {
  return str.split("\n").map(line => line.split(","));
}

const csv = "name,age\nAlice,25\nBob,30";
console.log(parseCSV(csv));
// Find duplicates in array

function findDuplicates(arr) {
  const seen = new Set();
  const duplicates = new Set();
  for(const num of arr) {
    if(seen.has(num)) duplicates.add(num);
    else seen.add(num);
  }
  return [...duplicates];
}

console.log(findDuplicates([1,2,3,2,4,1])); // [1,2]
# Day 32 - DeFi Risks

- Smart contract bugs
- Impermanent loss
- Market volatility
- Regulatory risks
// Simple countdown timer

function countdown(seconds) {
  const interval = setInterval(() => {
    console.log(seconds);
    seconds--;
    if(seconds < 0) clearInterval(interval);
  }, 1000);
}

countdown(5);
// Count characters in string

function charCount(str) {
  const count = {};
  for(const char of str) {
    count[char] = (count[char] || 0) + 1;
  }
  return count;
}

console.log(charCount("hello"));
// Check if string is a valid URL

function isValidURL(str) {
  try {
    new URL(str);
    return true;
  } catch {
    return false;
  }
}

console.log(isValidURL("https://github.com")); // true
console.log(isValidURL("invalid-url")); // false
// Sum numbers recursively

function sumRec(n) {
  if(n <= 0) return 0;
  return n + sumRec(n-1);
}

console.log(sumRec(5)); // 15
# Day 38 - DAOs

- Decentralized Autonomous Organization
- Rules encoded in smart contracts
- Members vote on proposals
- No central authority
# Day 38 - DAOs

- Decentralized Autonomous Organization
- Rules encoded in smart contracts
- Members vote on proposals
- No central authority// Simple bot responding to commands

function bot(command) {
  if(command === "hello") return "Hi!";
  if(command === "time") return new Date().toLocaleTimeString();
  return "Unknown command";
}

console.log(bot("hello"));
console.log(bot("time"));
// Merge two arrays

function mergeArrays(a, b) {
  return [...a, ...b];
}

console.log(mergeArrays([1,2],[3,4])); // [1,2,3,4]
# Day 41 - Airdrops

- Free tokens distributed by projects
- Usually require wallet registration
- Check legitimacy to avoid scams
// Node.js: move file example

const fs = require('fs');
fs.rename('example.txt', 'folder/example.txt', err => {
  if(err) console.error(err);
  else console.log('File moved!');
});
// Node.js: move file example

const fs = require('fs');
fs.rename('example.txt', 'folder/example.txt', err => {
  if(err) console.error(err);
  else console.log('File moved!');
});
// Simple 2D matrix example

const matrix = [
  [1,2,3],
  [4,5,6],
  [7,8,9]
];

console.log(matrix[1][2]); // 6
# Day 44 - Tokenomics

- Token supply & distribution
- Utility vs governance tokens
- Incentives for users
- Inflation/deflation dynamics
// Parse and stringify JSON

const obj = {name: "Alice", age: 25};
const jsonStr = JSON.stringify(obj);
console.log(jsonStr);

const parsed = JSON.parse(jsonStr);
console.log(parsed.name);
// Print triangle pattern

for(let i = 1; i <= 5; i++){
  console.log('*'.repeat(i));
}
# Day 47 - Layer 2

- Scaling solutions for Ethereum
- Faster and cheaper transactions
- Examples: Arbitrum, Optimism
const fetch = require('node-fetch');

async function getPrice() {
  const res = await fetch('https://api.coindesk.com/v1/bpi/currentprice.json');
  const data = await res.json();
  console.log(`BTC: ${data.bpi.USD.rate}`);
}

getPrice();
// Simple stack and queue using arrays

const stack = [];
stack.push(1);
stack.push(2);
console.log(stack.pop()); // 2

const queue = [];
queue.push(1);
queue.push(2);
console.log(queue.shift()); // 1
# Day 50 - Security Basics

- Keep private keys safe
- Use strong passwords
- Avoid phishing links
- Verify smart contracts
<!DOCTYPE html>
<html>
<head>
  <title>Calculator</title>
</head>
<body>
  <input id="num1" type="number" placeholder="Number 1">
  <input id="num2" type="number" placeholder="Number 2">
  <button onclick="calculate()">Add</button>
  <p id="result"></p>

  <script>
    function calculate() {
      const a = Number(document.getElementById('num1').value);
      const b = Number(document.getElementById('num2').value);
      document.getElementById('result').innerText = a + b;
    }
  </script>
</body>
</html>
// Add multiply & subtract functionality

function add(a,b){return a+b;}
function subtract(a,b){return a-b;}
function multiply(a,b){return a*b;}

console.log(add(2,3)); // 5
console.log(subtract(5,2)); // 3
console.log(multiply(3,4)); // 12
<!-- Added subtract and multiply buttons -->
<input id="num1" type="number">
<input id="num2" type="number">
<button onclick="addNums()">Add</button>
<button onclick="subtractNums()">Subtract</button>
<button onclick="multiplyNums()">Multiply</button>
<p id="result"></p>
<script>
function addNums() {
  const a = Number(document.getElementById('num1').value);
  const b = Number(document.getElementById('num2').value);
  document.getElementById('result').innerText = a + b;
}
function subtractNums() {
  const a = Number(document.getElementById('num1').value);
  const b = Number(document.getElementById('num2').value);
  document.getElementById('result').innerText = a - b;
}
function multiplyNums() {
  const a = Number(document.getElementById('num1').value);
  const b = Number(document.getElementById('num2').value);
  document.getElementById('result').innerText = a * b;
}
</script>
# Day 54 - Web3 Tools

- ethers.js: interact with Ethereum
- web3.js: alternative library
- Hardhat: test/deploy smart contracts
- Metamask: wallet integration
<input id="todoInput" placeholder="Add task">
<button onclick="addTask()">Add</button>
<ul id="tasks"></ul>
<script>
function addTask() {
  const val = document.getElementById('todoInput').value;
  const li = document.createElement('li');
  li.textContent = val;
  document.getElementById('tasks').appendChild(li);
}
</script>
// Save todos to localStorage

function addTask() {
  const val = document.getElementById('todoInput').value;
  let tasks = JSON.parse(localStorage.getItem('tasks')||'[]');
  tasks.push(val);
  localStorage.setItem('tasks', JSON.stringify(tasks));
  renderTasks();
}

function renderTasks() {
  const tasks = JSON.parse(localStorage.getItem('tasks')||'[]');
  const ul = document.getElementById('tasks');
  ul.innerHTML = '';
  tasks.forEach(task => {
    const li = document.createElement('li');
    li.textContent = task;
    ul.appendChild(li);
  });
}
renderTasks();
// Add delete button for each task

function renderTasks() {
  const tasks = JSON.parse(localStorage.getItem('tasks')||'[]');
  const ul = document.getElementById('tasks');
  ul.innerHTML = '';
  tasks.forEach((task, index) => {
    const li = document.createElement('li');
    li.textContent = task;
    const delBtn = document.createElement('button');
    delBtn.textContent = 'Delete';
    delBtn.onclick = ()=>deleteTask(index);
    li.appendChild(delBtn);
    ul.appendChild(li);
  });
}

function deleteTask(index) {
  let tasks = JSON.parse(localStorage.getItem('tasks')||'[]');
  tasks.splice(index,1);
  localStorage.setItem('tasks', JSON.stringify(tasks));
  renderTasks();
}
// Add delete button for each task

function renderTasks() {
  const tasks = JSON.parse(localStorage.getItem('tasks')||'[]');
  const ul = document.getElementById('tasks');
  ul.innerHTML = '';
  tasks.forEach((task, index) => {
    const li = document.createElement('li');
    li.textContent = task;
    const delBtn = document.createElement('button');
    delBtn.textContent = 'Delete';
    delBtn.onclick = ()=>deleteTask(index);
    li.appendChild(delBtn);
    ul.appendChild(li);
  });
}

function deleteTask(index) {
  let tasks = JSON.parse(localStorage.getItem('tasks')||'[]');
  tasks.splice(index,1);
  localStorage.setItem('tasks', JSON.stringify(tasks));
  renderTasks();
}
# Day 58 - Smart Contract Flow

1. Write contract in Solidity
2. Compile using Hardhat/Remix
3. Deploy to testnet
4. Interact via Web3/ethers.js
5. Test & audit
// Fetch and display cryptocurrency prices

async function fetchPrice() {
  const res = await fetch('https://api.coindesk.com/v1/bpi/currentprice.json');
  const data = await res.json();
  document.getElementById('btcPrice').innerText = `BTC: $${data.bpi.USD.rate}`;
}
fetchPrice();
// Filter coins by min price (example)

function filterCoins(coins, minPrice) {
  return coins.filter(c => c.price >= minPrice);
}
<style>
body { font-family: Arial; }
#btcPrice { font-weight: bold; color: green; }
</style>
<p id="btcPrice"></p>
<script src="dashboard.js"></script>
# Day 62 - Oracles

- Provide off-chain data to smart contracts
- Examples: Chainlink
- Key for DeFi apps needing real-world data
// Track multiple coins (example)

const coins = ['BTC','ETH','DOGE'];

async function getPrices() {
  for(const coin of coins) {
    const res = await fetch(`https://api.coingecko.com/api/v3/simple/price?ids=${coin.toLowerCase()}&vs_currencies=usd`);
    const data = await res.json();
    console.log(`${coin}: $${data[coin.toLowerCase()].usd}`);
  }
}

getPrices();
// Alert if price > threshold

const threshold = 50000;

async function checkBTC() {
  const res = await fetch('https://api.coindesk.com/v1/bpi/currentprice.json');
  const data = await res.json();
  const price = parseFloat(data.bpi.USD.rate.replace(',',''));
  if(price > threshold) alert(`BTC > $${threshold}`);
}

checkBTC();
// Reduce API calls, batch requests
# Day 66 - Bridges

- Connect different blockchains
- Enable token transfers cross-chain
- Risk: exploits, liquidity issues
// Add new commands: greet, time, BTC price

async function bot(command) {
  if(command==="hello") return "Hi!";
  if(command==="time") return new Date().toLocaleTimeString();
  if(command==="btc") {
    const res = await fetch('https://api.coindesk.com/v1/bpi/currentprice.json');
    const data = await res.json();
    return `BTC: ${data.bpi.USD.rate}`;
  }
  return "Unknown command";
}
// Add new commands: greet, time, BTC price

async function bot(command) {
  if(command==="hello") return "Hi!";
  if(command==="time") return new Date().toLocaleTimeString();
  if(command==="btc") {
    const res = await fetch('https://api.coindesk.com/v1/bpi/currentprice.json');
    const data = await res.json();
    return `BTC: ${data.bpi.USD.rate}`;
  }
  return "Unknown command";
}
// Only alert if new task exists

let tasks = [];

setInterval(() => {
  const newTask = Math.random() > 0.5;
  if(newTask) {
    console.log("New task detected!");
    tasks.push(Date.now());
  }
}, 10000);
# Day 70 - MEV Basics

- Miner/Maximal Extractable Value
- Arbitrage opportunities in DeFi
- Can affect transaction ordering
- Risks for regular users
// Simple crypto portfolio tracker

let portfolio = {
  BTC: 0.5,
  ETH: 2
};

async function getPortfolioValue() {
  const resBTC = await fetch('https://api.coindesk.com/v1/bpi/currentprice/BTC.json');
  const dataBTC = await resBTC.json();
  const btcUSD = parseFloat(dataBTC.bpi.USD.rate.replace(',',''));

  const resETH = await fetch('https://api.coingecko.com/api/v3/simple/price?ids=ethereum&vs_currencies=usd');
  const dataETH = await resETH.json();
  const ethUSD = dataETH.ethereum.usd;

  const total = portfolio.BTC*btcUSD + portfolio.ETH*ethUSD;
  console.log(`Total Portfolio Value: $${total.toFixed(2)}`);
}

getPortfolioValue();
// Track gains/losses (mock example)

const history = [1000, 1050, 1020, 1100];

function computeGains(arr){
  for(let i=1;i<arr.length;i++){
    console.log(`Day ${i}: ${arr[i]-arr[i-1]} USD`);
  }
}

computeGains(history);
<p id="value"></p>
<script src="portfolio.js"></script>
<style>
  #value { font-weight: bold; color: blue; }
</style>
# Day 74 - Scaling

- Layer 2 solutions
- Sidechains
- Sharding
- Reduce gas and increase TPS
<!DOCTYPE html>
<html>
<body>
<button id="connect">Connect Wallet</button>
<p id="status"></p>
<script src="https://cdn.jsdelivr.net/npm/ethers/dist/ethers.min.js"></script>
<script>
  const btn = document.getElementById('connect');
  const status = document.getElementById('status');

  btn.onclick = async () => {
    if(window.ethereum){
      await window.ethereum.request({ method: 'eth_requestAccounts' });
      status.innerText = 'Wallet Connected';
    } else status.innerText = 'Install MetaMask';
  }
</script>
</body>
</html>
