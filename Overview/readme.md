


## 1. Understanding the Main Parts

BOS involves three main parts: Chain, Components, and Gateways. They work together, forming a unique stack of technologies. This guide will use the terminology of backend (Chain) and frontend (Components and Gateways) for clarity. The visual stack representation is as follows:

- Gateway
  - Application Layer
  - EC2 HTTP Server
- Components
  - HTTP API
  - JS SDK
- Chain (Smart Contract)
  - SDK and NEAR API
  - Blockchain
    - EC2 Server


from the official docs:
> The Blockchain Operating System (BOS) simplifies building, deploying and accessing decentralized frontends. Embrace the power of community and Web 3.


## 2. Introducing the Chains

For our BOS, we use an EVM-based chain. This guide will focus on the NEAR Protocol, which operates on nodes, including validators generating blocks and regular nodes propagating data. We'll also use Smart Contracts written in a language compatible with the NEAR platform's API or SDK.

## 3. The Role of Components

In the context of a decentralized web application, JavaScript-based components are employed to interact with the destination chain, in this case, NEAR. Familiarity with frontend frameworks like ReactJS would be beneficial as components share similar properties. This guide will focus on three types of components:

- Built-In Components
- Widget and iFrame Components
- Custom Components

## 4. Exploring Gateways and VMs

A gateway is an interface into the blockchain, operating on a regular HTTP server and utilizing components to invoke the SDK. What sets it apart from normal web apps is its ability to dynamically reference the components of the app. Included within each Gateway is a JavaScript package known as the Virtual Machine (VM), which allows code to be run safely and securely.

## 5. Utilizing Tools

NEAR Protocol provides a set of tools known as NEAR DEV Tools that will aid you in your journey of building on the BOS.

## 6. Customizing Gateways and VMs

You can customize the Gateways and VMs by adding new libraries and making them accessible to your application.

## 7. Deploying App Fully On BOS

Finally, the deployment of the app involves setting up the smart contract with the DEV Hub and setting up the frontend.




---




