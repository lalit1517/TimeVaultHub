# TimeVaultHub

TimeVaultHub is a cutting-edge online platform where managing your funds has never been more intuitive and rewarding. TimeVaultHub provides a seamless experience for users to top up their accounts and watch their investments grow through a sophisticated compounding mechanism.

## Features

- **users are greeted by a sleek and user-friendly interface. The dashboard prominently displays their current account balance, providing a quick overview of their financial status.**
- 
- **Once the user initiates a top-up, our advanced compounding system kicks in. The system dynamically calculates and compounds the amount based on the current time, ensuring that users benefit from the most favorable returns.** 

- **Users can seamlessly initiate withdrawals whenever they wish. The withdrawal process is straightforward, and funds are transferred securely to the linked account. Users have full control over their financial decisions.**
- 
- **After any transaction, users can review and finalize their actions. The "Finalize Transaction" feature provides a comprehensive summary, detailing the top-up or withdrawal amount, the compounded interest accrued, and the resulting account balance.** 

## Running the project locally

If you want to test your project locally, you can use the following commands:

```bash
# Starts the replica, running in the background
dfx start --background

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```

Once the job completes, your application will be available at `http://localhost:8000?canisterId={asset_canister_id}`.

Additionally, if you are making frontend changes, you can start a development server with

```bash
npm start
```

which will start a server at `http://localhost:8080`, proxying API requests to the replica at port 8000.
