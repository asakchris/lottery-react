# Interactive front-end (React JS) for Lottery Ethereum smart contract
### How to run this project?
1. Clone this repository
1. Use any editor/command line tool and run `npm install` from root directory to download all dependencies
1. Clone [lottery smart contract](https://github.com/asakchris/lottery) repository
1. Follow the instructions in `lottery` and run `node deploy.js`.
   It creates ABI & byte code of the contract and print ABI in the console log.
   Also it deploys the instance of the lottery contract in Rinkeby Test Network and print it in the console log.
1. Update [lottery.js](./src/lottery.js) with ABI & contract address from previous step
1. Run the application using `npm run test`, it start the app and open it in the browser
1. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
