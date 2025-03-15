# Solana Payment App  

## **Overview**  
This project is a **simple Solana-based payment application** built using **HTML, CSS, and JavaScript**. The app allows users to **connect their Phantom Wallet, enter a SOL amount, and send transactions** to a predefined wallet address.  

## **How to Run the Project**  
1. **No installation is required** – simply open the `index.html` file in a web browser.  
2. Click the **"Connect"** button to link your Phantom Wallet.  
3. Enter the amount of SOL to send.  
4. Click **"Send"** to transfer SOL to the recipient.  

## **Features**  
✅ **Wallet Connection** – Connects to the Phantom Wallet (Solana-based).  
✅ **Transaction Processing** – Sends SOL to a predefined wallet address.  
✅ **User-Friendly Interface** – Simple input field for SOL amount with status updates.  
✅ **Mobile Support** – Redirects mobile users to the Phantom Wallet app.  

## **Technology Stack**  
- **Frontend:** HTML, CSS, JavaScript  
- **Blockchain:** Solana Web3.js  
- **Wallet Support:** Phantom Wallet  
- **API Integration:** Solana RPC Network  

## **Project Files**  
- `index.html` – Main file to run the project.  
- `index.css` – Stylesheet for the app.  
- `main.js` – JavaScript logic for wallet connection and transactions.  

## **How the Payment Works**  
1. The app **detects if Phantom Wallet is installed**.  
2. If the user clicks **"Connect"**, the wallet connection is initiated.  
3. The user enters the **SOL amount** to send.  
4. Clicking **"Send"** initiates a **Solana transaction** to the recipient's wallet.  
5. A **confirmation message** is displayed after a successful transfer.  

## **Dependencies**  
This project uses **Solana Web3.js** to interact with the blockchain. The required script is included:  

```html
<script src="https://unpkg.com/@solana/web3.js@v1.33.0/lib/index.iife.js"></script>
