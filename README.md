![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/2da10d41-290c-433f-ae65-799404226a1e)# Eclipse-Testnet-Interaction

__________________
## Amount Raised 
Eclipse raised a total of $65M HackVC, Polychain Capital among other Investors 
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/2d2c5a3e-ae73-4991-ba2b-eb4eeb9de915)

----------------


## Gettings Started 
### Installing Perequisite 
```
sudo apt update
sudo apt upgrade -y
```


### Install Rust 

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Reply with ```1```
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/fab76dcb-58a7-434d-a562-84b0c114ee68)


### Environment Variable  

```
. "$HOME/.cargo/env"
```
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/88642b35-113d-4533-a90a-504b776eab79)


### check ```RUST version```

```
rustc --version
```


## Install Solana CLI 

```
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
```
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/d6899685-c5f1-4847-b2e9-961110f7ac27)


```
export PATH="/root/.local/share/solana/install/active_release/bin:$PATH"
```
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/d84a6528-13c8-4fa0-aa2f-713e2711019d)


### check version if installed properly 
```
solana --version
```
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/0bc063f2-bf08-48f5-a8d4-aeb40a908085)




### Install dependencies 
Reply with ```y``` and proceed 
```
sudo apt-get update
sudo apt-get install nodejs
sudo apt-get install npm
npm install --global yarn

```


### Checking version 
```
node -v
npm --version
yarn --version
```
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/d092269e-ef9b-4dd8-9d2d-44b1960f8163)



# Install Anchor 

```
cargo install --git https://github.com/project-serum/anchor anchor-cli --locked
```
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/9b298626-c729-4f3c-8a97-0fba972d7494)


-------------------

### Check version 
```
anchor --version
```
------------


## Create a Solana Wallet 
```
solana-keygen new -o /path-to-wallet/my-wallet.json
```
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/5ebb84f3-8c57-4fdd-af89-b72d58373470)


Press ```ENTER``` ans save the Info 
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/dc67db2f-e5aa-44d6-b033-882a96573d0c)




## Update configuration to use new wallet
```
solana config set --url https://testnet.dev2.eclipsenetwork.xyz/
```
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/5e778d24-6df2-4ce9-a152-6e4d2fa8bc27)

```
solana config set --keypair /path-to-wallet/my-wallet.json

```

### Save Solana address 
```
solana address
```


-----------------------

# Import the same seedphrase to Metamask/Rabby Wallet --- for we are gonna send Ethereum Sepolia to it 
## I renamed it so i won't mix it up with my wallet 

![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/e6a55210-d6a4-45de-a708-d599238bd841)

### Request Sepolia gas on your main wallet: 
MINE SEPOLIA GAS  ---https://sepolia-faucet.pk910.de/
Request from Quicknode ---  https://faucet.quicknode.com/ethereum/sepolia 
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/3ec18a31-9b77-4fc7-876e-bd383d10ad1b)
![image](https://github.com/mztacat/Eclipse-Testnet-Interaction/assets/31314340/7196a7bd-0b77-43db-8640-9d1434c6ba52)




---------------------


















