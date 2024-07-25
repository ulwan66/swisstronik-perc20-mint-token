# Swisstronik Tesnet Techinal Task 4 (Mint a PERC20 Token)

link : [Click!](https://www.swisstronik.com/testnet2/dashboard)

Feel free donate to my EVM address

EVM :

```bash
0x6c34be1ec3f1d3a55d40cdedaeccd7772ac30d44
```

## Steps

### 1. Clone Repository

```bash
git clone https://github.com/ulwan66/swisstronik-perc20-mint-token.git
```

```
cd swisstronik-perc20-mint-token
```

### 2. Install Dependency

```bash
npm install
```

### 3. Set .env File

create .env file in root project

```bash
PRIVATE_KEY="a99a343b964580e8b199c7a86798201d4d746cf18296e444e754372ac80b962d"
```

### 4. Update Smart Contract (Skipp if you won't modify Token name)

- Open contracts folder
- Open PERC20Sample.sol file
- Feel free to modify token name and token symbol

### 5. Compile Smart Contract

```bash
npm run compile
```

### 6. Deploy Smart Contract

```bash
npm run deploy
```

### 7. Mint Token

```bash
npm run mint
```

### 8. Transfer Token

```bash
npm run transfer
```

### 8. Finsihed

- Open the deployed-adddress.ts (location in utils folder)
- Copy the address and paste the address into testnet dashboard
- Open the tx-hash.txt (location in utils folder)
- Copy the address and paste the tx hash link into testnet dashboard
- push this project to your github and paste your repository link in testnet dashboard

by :
github : [ulwan66](https://github.com/ulwan66)
twitter : @NardeTesi
telegram : @killwqn

0xCd825ae0335190f4c8882DF16FB0577d478b3898
