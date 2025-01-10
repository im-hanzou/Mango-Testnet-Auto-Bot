## MANGO TESTNET AUTO BOT

**Register** : [HERE](https://task.testnet.mangonetwork.io/?invite=Hkm9nF)

- [Download Mango Wallet Extension](https://chromewebstore.google.com/detail/mango-wallet/jiiigigdinhhgjflhljdkcelcjfmplnd)
- Backup Phrase
- Claim Faucet on your Wallet extension
- Go To [Web](https://task.testnet.mangonetwork.io/?invite=d9q5MS) 
- Complete Bind Social Media Accounts and JOIN NOW
- Go to [Event Page](https://task.testnet.mangonetwork.io/events)
- Complete Task on the Task List ( Swap , Bridge )
- Login Daily
- Done

**LFG**

## PREREQUISITE

- Git
- Node JS (v22)

 ## BOT FEATURE

- Multi Account 
- Support PK
- Proxy Support
- Daily Claim Faucet
- Daily Mango Swap 
- Daily BeingDex Beta DAPP
- Daily Check In
- Daily Bridge 

## SETUP & CONFIGURE BOT

### LINUX

1. Clone project repository
   ```
   git clone https://github.com/airdropinsiders/Mango-Testnet-Auto-Bot.git && cd Mango-Testnet-Auto-Bot
   ```
2. Install Dependencies and Setup Accounts
   ```
   npm install && npm run setup
   ```
3. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
4. Configure the bot config
    ```
   nano config/proxy_list.js
    ```
5. To run Auto TX
   ```
   npm run start
   ```
   
### WINDOWS

1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repository
   ```
   git clone https://github.com/airdropinsiders/Mango-Testnet-Auto-Bot.git
   ```
   and cd to project dir
   ```
   cd Mango-Testnet-Auto-Bot
   ```
3. Install Dependencies and Setup Accounts 
   ```
   npm install && npm run setup
   ```
5. Navigate to `Mango-Testnet-Auto-Bot` directory. 
6. Navigate to `accounts` directory.
7. Now open `acccounts.js` and setup your accounts. 
8. Now Back to `Mango-Testnet-Auto-Bot` directory and Navigate to `config` directory and adjust the `proxy_list.js` as needed.
9.  Back to `Mango-Testnet-Auto-Bot` directory.
10. To start the app open your `Command Prompt` or `Power Shell`
11. To run auto Tx Bot
    ```
    npm run start
    ```

## UPDATE BOT

To update bot follow this step :
1. Run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   If error run
   ```
   git stash && git pull
   ```
2. Run
   ```
   npm update
   ```
3. Start the bot
4. If any eror happen check `log/app.log`


## IMPORTANT NOTE (READ IT THIS IS NOT DECORATION)
DWYOR & Always use a new wallet when running the bot, I am not responsible for any loss of assets.

## LICENSE

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
