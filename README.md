### Linkler
 * [Hercules Telegram](https://t.me/HerculesNode)
 * [Hercules Twitter](https://twitter.com/Herculesnode)


- Cyber Testnet ve mainnet ağında deposit ve Nft mint işlemi


### Testnet

| Testnet Bilgiler |      |     Mainnet  |    
| :-------- | :------- |  :-------      | 
| Network Name	      | Cyber Testnet |    Cyber    |  
| RPC Endpoint	      | https://cyber-testnet.alt.technology/ |  https://cyber.alt.technology/     |  
| Chain ID	      | 	111557560 |     7560   |   	 |  
| Currency Symbol	      | ETH |     ETH   |    |  
| Block Explorer      | 	https://testnet.cyberscan.co/|     https://cyberscan.co/  |   


### Testnet Sepolia Musluk ve bridge

- https://sepoliafaucet.com/  bu adresten sepolia ETH temin edin.
- https://cyber-testnet.testnets.rollbridge.app/  Bu adresten Sepolia ETH - Cyber Testnet ağına aktarın.

### Mainnet ETH bridge

- https://cyber.co/bridge  Bu adresten  ETH - Cyber Mainnet ağına aktarın. Fee yüksek biraz

### Kurulum 

- foundryup kurulumu yapın.

```shell
curl -L https://foundry.paradigm.xyz | bash
```

```shell
source /root/.bashrc
```

```shell
foundryup
```

-  Proje ismi belirleyin

```shell
forge init PROJE-İSMİ
```

```shell
cd PROJE-İSMİ
```

### Deploy edin ( TESTNET )

- Testnet için aşağıdaki kod kullanın Sepolia ETH yatırdığınız MM cüzdanınızın private keyni yazacaksınız.

```shell
forge create --rpc-url "https://cyber-testnet.alt.technology/" --private-key CÜZDAN-PRİVATE-KEY-YAZIN  src/Counter.sol:Counter
```


### Deploy edin ( Mainnet )

```shell
forge create --rpc-url "https://cyber.alt.technology/" --private-key CÜZDAN-PRİVATE-KEY-YAZIN src/Counter.sol:Counter
```


- işlem sonunda size  aşağıdakileri verecek kaydedin bir yere
-Deployer
-Deployed to:
-Transaction hash:

### Kontrol

- Testnet explorer : https://testnet.cyberscan.co/
- Mainnet Explorer : https://cyberscan.co/


### Form

işlem sonunda aşağıdaki formu doldurun ve discord kanallarına girin.

- Form : https://cyber.deform.cc/ecosystem-builder/
- discord : https://discord.gg/buildoncyber
