# jubilant-octo-adventure
https://github.com/Hifzi17/jubilant-octo-adventure/edit/main/README.md
# Prerequisites
1. Node.js installed on your machine
2. npm or yarn package manager
# Installation
1.Clone the repository:
git clone https://github.com/dante4rt/sonic-odyssey-bot.git
Navigate into the project directory:

cd sonic-odyssey-bot
# Install dependencies:
npm install
# or
yarn install
Prepare input files:

Create accounts.json with an array of seed phrases.
Create privateKeys.json with an array of private keys (base58 encoded).
Example accounts.json:

[
  "seed_phrase_1",
  "seed_phrase_2"
]
Example privateKeys.json:

[
  "base58_private_key_1",
  "base58_private_key_2"
]
Usage
Run the bot using Node.js:

npm start
Follow the prompts to:

Select the input method (0 for seed phrase, 1 for private key).
Specify the number of random addresses to generate.
Enter the amount of SOL to send in each transaction.
Enter the delay between each transaction in milliseconds (default is 1000ms).
Contributing
Contributions are welcome! Feel free to open issues or pull requests for any improvements or fixes.
