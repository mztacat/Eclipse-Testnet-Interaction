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














