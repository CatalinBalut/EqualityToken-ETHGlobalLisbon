## Quick start
The first things you need to do are cloning this repository and installing its
dependencies:


### Prerequisites
Add `.secrets.json` file in root directory and put your secret phrase as a json format. For example:
```
{
    "mnemonic":"crazy crazy crazy crazy crazy crazy crazy crazy crazy crazy crazy buzz"
}
```

Then, on a new terminal, go to the repository's root folder and run this to
deploy your contract:

```sh
npx hardhat run scripts/deploy.js --network polygon_mumbai
```

# XEN token address 

| Contract name            | Mumbai address|  
| ------------------------ | -------------------|
| EqualityToken                | 0xdaa5c46776fabecb51226a0b84b3613c04976abe|