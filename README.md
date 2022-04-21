# fabric-external-asset-transfer-basic

This project serves as a guide for running the [asset-transfer-basic](https://github.com/hyperledger/fabric-samples/tree/main/asset-transfer-basic/chaincode-external) 
[Chaincode as a Service](https://hyperledger-fabric.readthedocs.io/en/latest/cc_service.html) and using [Chaincode External Builders](https://hyperledger-fabric.readthedocs.io/en/latest/cc_launcher.html) 
configured for Kubernetes.

A sample integration is available with the [Kubernetes Test Network](https://github.com/jkneubuh/fabric-samples/tree/main/test-network-k8s)


## Quickstart

```shell 
docker run \
  --rm \
  -e CHAINCODE_SERVER_ADDRESS=0.0.0.0:9999 \
  -e CHAINCODE_ID=basic_1.0:e47a28f7406718bb0c6cefb00a6a6167099bf2d426e802d417f54c32d1a1ea1b \
  -p 9999:9999 \
  ghcr.io/hyperledgendary/fabric-external-asset-transfer-basic 
``` 


## Building the Image


## Publishing the Image 


## Updating the Chaincode Deployment 
