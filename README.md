# Concordium Hack TASK 01
##### By Grigore-Gabriel Trifan (GregTrifan)
##### Concordium Mainnet adress: ```2xBLr1bosK5NEQJTW9q1GHsmmuDgLrjAAzC8CSUBJc55AwVsw5```
##### Ethereum address: ```0x2BA30F26B0D163cDFEEA21B9eaC8f82f1Afaa021```
**!!! The address filled on Gitcoin is the Concordium Mainnet one rather than an ERC-20 address**
* Install Rust
  ![](img/rust-cfg-01.png)
  ![](img/rust-cfg-02.png)
  * Install Wasm toolset
  
  ![](img/rust-cfg-03.png)
* cargo-concordium config
    ![](img/concordium-cfg-01.png)
* Web Wallet config
    * Create account (Address ```48HEZQ7wZU2S1fenyQzt9Ms5K3R4yMHyUtwUqkoREHsFW7zcHb```)
        ![](img/account-01.png)
    * Requested 2000 CCD from the Faucet  
    ( txHash: ```04996e4544182f5efe2adabc35c65703660580a7244a02479017b68598622d11``` )
        ![](img/faucet-result.png)
    * Export account for concordium-client

        ![](img/account-02.png)
* concordium-client config
    * installed concordium-client
     ![](img/concordium-cfg-02.png)
    * added account concordium-client from web wallet
     **exported account data from web wallet**
      ![](img/account-details.png) 
      **imported account to concordium-client**
     ![](img/account-03.png)
