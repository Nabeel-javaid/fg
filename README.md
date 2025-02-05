
This project interacts with various APIs including Twitter and CoinMarketCap. To get started, follow the setup instructions below to configure your environment and provide the necessary credentials.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/VeritasAnalytica/TweetChain
   cd TweetChain
   ```

2. **Rename the `.env.example` file:**
   In the root directory of the project, you'll find a file named `.env.example`. Rename it to `.env`:

   ```bash
   mv .env.example .env
   ```

3. **Set your credentials:**
   Open the `.env` file in a text editor, and replace the placeholder values with your actual credentials:

   - `OPENAI_API_KEY=<your-openai-api-key>`
   - `TWITTER_USERNAME=<your-twitter-username>`
   - `TWITTER_PASSWORD=<your-twitter-password>`
   - `TWITTER_EMAIL=<your-twitter-email>`
   - `TWITTER_2FA_SECRET=<your-twitter-2fa-secret>` *(only if you have 2FA enabled)*

   You will also need to add the following Twitter API credentials:

   - `TWITTER_API_KEY=<your-twitter-api-key>`
   - `TWITTER_API_SECRET=<your-twitter-api-secret>`
   - `TWITTER_ACCESS_TOKEN=<your-twitter-access-token>`
   - `TWITTER_ACCESS_TOKEN_SECRET=<your-twitter-access-token-secret>`
   - `ALCHEMY_API_KEY` =< your alchemy api key
   - `WALLET_ADDRESS` =< the wallet address you want to track

4. **Important Notes:**
   - There may be cases where the CoinMarketCap API provides incorrect or outdated information. Unfortunately, we have no control over this, and it may not be something that can be fixed on our end. Please be aware of this limitation while using the application.

## Running the Project

Once you have completed the setup, you should be ready to run the project. Ensure that all dependencies are installed, and follow the instructions in the project for how to run it.

```pnpm i --no-frozen-lockfile```
and once it is done you can run 
```pnpm build``` to build the code


## License

Include your license information here, if applicable.

```

This format provides a clear set of instructions for setting up the environment and includes all the necessary credentials. It also explains the potential issue with CoinMarketCap data and makes it easy for others to get started with the project.
