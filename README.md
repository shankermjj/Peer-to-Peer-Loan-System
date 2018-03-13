# Blockchain-SimpleInterest-Dapp
It is Basic Dapp for Blockchain, Creation using Solidity Smartcontract+Truffle+JS using HTML+CSS as front end

# Installation:
1.First, update and install packages
      $ sudo apt-get update && sudo apt-get -y upgrade
      $ sudo apt-get -y install curl git vim build-essential
2.Install NodeJs to execute the DAPP
      $ curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
      $ sudo apt-get install -y nodejs
      $ sudo npm install -g express
3. Install Truffle packages
      $ sudo npm install -g truffle
4. Install testrpc(testprc uses ethereumjs to simulate full client behavior and make developing Ethereum)
    $ sudo npm install -g ethereumjs-testrpc
  
 Clone: 
 clone the repository to your project Directory <br />

# Execution:
1. Open a terminal & change the directory to SimpleInterest-Dapp & run following Commands
      $ truffle compile            //compiling solidity files <br />

2. Open a another terminal and run TestRPC as Dummy Blockchain
      $ testrpc <br />
   
3. Again open a first Terminal for Remaining Execution <br />
      $ truffle migrate <br />
      $ npm run dev <br />
          pick the url: https://localhost:8080 <br />
4. Then, Paste url in Browser

