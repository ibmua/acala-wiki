# Connect to a Node

To use Acala EVM, you need to connect to an Acala Node. You can either

1. connect to a deployed test network \(maintained by Acala\) OR
2. run a local Acala test node

### **1. Connect to a deployed test network**

Find all available testnet nodes [here](https://wiki.acala.network/learn/get-started/public-nodes#mandala-test-network-nodes)

### **2. Run a local Acala test node**

Alternatively, you can run a local test node. To run your own node, you need to have installed [Docker](https://www.docker.com/) on your machine. If you don’t have it installed, please follow the instructions [here](https://docs.docker.com/get-docker/).

To check whether Docker is successfully installed run the command below:

```text
docker version
```

If you receive the version number, you can start your local Acala node with the command below:

```text
docker run -it -p 9944:9944 -p 9933:9933 acala/aca-node:latest --dev --ws-external --rpc-external
```

The output of your node should look like this:

![](https://i.imgur.com/EyryyFs.png)
