# Replicate deploying and running:

prerequisites:
- fill .env with MNEMONIC and PROJECT_ID (infura api key)
- git config --global url.https://github.com/.insteadOf git://github.com/
- npm install / npm install --save-dev

migrate, build and deploy:
(- truffle compile)
- truffle migrate --network sepolia
- webpack

run:
- npm run-script web-dev