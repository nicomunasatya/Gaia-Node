# Gaia-Node
Running Gaia Node using rental GPU in Hyperbolic
Using this method you can double earning from confirmed incentive airdrop Gaia Node and retroactive Hyperbolic
Below Fundrasing Gaia and Hyperbolic

![Fundraising Gaia](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/fundraising%20gaia.jfif)
![Fundraising Hyperbolic](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/hyperbolic%20fundraising.png)

Prerequisites
Before you get started, ensure that you have the following on your system:

System	Minimum Requirements :

OSX with Apple Silicon (M1-M4 chip)	16GB RAM (32GB recommended)

Ubuntu Linux 20.04 with Nvidia CUDA 12 SDK	8GB VRAM on GPU

Azure/AWS	Nvidia T4 GPU Instance

1. First, [Login Hyperbolic](https://app.hyperbolic.xyz/) continue with Google

   ![Login](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/login.png)
2. Go to menu Setting and top up fund 5$ using crypto or visa

   ![Top up](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/top%20up.png)
3. Go to your terminal using your own device or you can use vps.To get your SSH public key on a Linux VPS, follow these steps:

   Run this in your terminal:
   ```
    ls ~/.ssh/id_rsa.pub
   ```
   If the file exists, you already have an SSH public key. To view it:
   ```
    cat ~/.ssh/id_rsa.pub
   ```

4. IMPORTANT copy your ssh public from your device/vps to ssh public hyperbolic in menu settings

   ![ssh public key](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/ssh%20public%20key.png)
5. Rent a GPU for example rent GPU RTX 3070 to rent for one hour pay 0.16 dollars

   ![Rent GPU](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/rent%20gpu.png)
6. Connect your rentu GPU to your device/VPS

   ![Connect GPU](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/connect.png)
7. When it's connected, congratulations, you can use it to work on the Gaia node

   ![ssh login vps](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/ssh%20login%20vps.PNG)
8. Installing the Gaia Node
  - Use the following command to download the latest version of the Gaia node:
  ```
  curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
  ```
  - Run the command printed on the terminal to set up the environment path, it is started with source.

   ![install gaia](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/install%20gaia.png)
  - Use the following command to initialize the Gaia node according to the configuration options in $HOME/gaianet/config.json. By default, the Gaia is initialized with a Llama 3.2 LLM and a knowledge base about Paris. This command could take some time since it will download a very large LLM file.
  ```
  gaianet init
  ```
  - Use the following command to start your node:
  ```
  gaianet start
  ```
  - A successful start prints a public URL for the node. Opening a browser to that URL will display the node information and allow you to chat with the AI agent on the node.
  ```
  #Example
  ... ... https://0xf63939431ee11267f4855a166e11cc44d24960c0.gaianet.xyz
  ```
  - To stop the node:
  ```
  gaianet stop
  ```
   - After get your node id and device id fill in the [Gaia Settings Node](https://www.gaianet.ai/setting/nodes), Create a new node and fill it
    
     if you haven't login in gaia you can login with your testnet wallet OKX or metamask

     ![setting node](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/setting%20node.png)

     ![add node](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/add%20node.png)

   - Check Your [Rewards Summary](https://www.gaianet.ai/reward-summary)
     
     ![add node](https://raw.githubusercontent.com/nicomunasatya/Gaia-Node/main/check%20gaia%20exp.png)
     
   
