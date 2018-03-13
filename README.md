# Blockchain-SimpleInterest-Dapp <br />
It is Basic Dapp for Blockchain, Creation using Solidity Smartcontract+Truffle+JS using HTML+CSS as front end <br />

# Installation: <br />
1.First, update and install packages <br />
      $ sudo apt-get update && sudo apt-get -y upgrade <br />
      $ sudo apt-get -y install curl git vim build-essential <br />
2.Install NodeJs to execute the DAPP <br />
      $ curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash - <br />
      $ sudo apt-get install -y nodejs <br />
      $ sudo npm install -g express <br />
3. Install Truffle packages <br />
      $ sudo npm install -g truffle <br />
4. Install testrpc(testprc uses ethereumjs to simulate full client behavior and make developing Ethereum) <br />
    $ sudo npm install -g ethereumjs-testrpc <br />
  
 Clone:  <br />
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

