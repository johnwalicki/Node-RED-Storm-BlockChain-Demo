# Node-RED-Storm-BlockChain-Demo
This is a Node-RED Dashboard that exercises a Hyperledger Composer REST API

Watch on developerWorks TV as I narrate how to
[Build a Blockchain app with Node-RED and Hyperledger Composer REST APIs](https://developer.ibm.com/tv/build-a-blockchain-app-with-node-red-and-hyperledger-composer-rest-apis/)

Feel free to review the [slides](Blockchain-NodeRED-Storm-InnovatorCall.pdf) from the webinar.

This repository contains the [Node-RED-Storm-Blockchain-Demo flow](Node-RED-Storm-Blockchain-Demo.json) that you might want to
experiment with to understand how Node-RED http request nodes can do GET / PUT calls into the Hyperledger Composer REST APIs.

The Node-RED dashboard manipulates the "Basic Storm" sample Business Network and its Hyperledger Composer model by creating Storm "assets", Alert "transactions", and changes Severity "properties".

The Node-RED dashboard consists of Forms, Dropdowns, Sliders, Gauges and Templates.  It's not intended to be a full application that FEMA would be interested in. The goal is to learn about the Composer REST APIs.
![Node RED Storm Blockchain dashboard annotated picture](Node-RED-Storm-Blockchain-dashboard-annotated.png?raw=true "Dashboard")

Here's a screenshot of the Node-RED flow that creates the above dashboard.
![Diagram Of BlockChain Node-RED flow](DiagramOfBlockChainNode-REDflow.png?raw=true "Flow Diagram")

I found the Hyperledger Composer swagger documentation very helpful while creating the Node-RED flow.
![HyperLedger REST API](HyperLedgerAPI-REST.png?raw=true "Hyperledger REST API screenshot")
The docs describe the parameters required for each REST API
![HyperLedgerAPI-Storm](HyperLedgerAPI-Storm.png?raw=true "Hyperledger REST API params")
All of the REST APIs are generated from the Hyperledger Composer Model:
![HyperLedger Model](HyperLedgerModel.png?raw=true "Hyperledger Model")
The model is defined in a Hyperledger Playground Business Network
![HyperLedger playground](HyperLedgerPlayground.png?raw=true "Hyperledger Playground example")
