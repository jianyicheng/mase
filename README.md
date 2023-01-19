# Machine-Learning Accelerator System Exploration Tools

This repo contains the following directories:
* `examples` - NN models by PyTorch
* `scripts` - Installation scripts  
* `Docker` - Docker container configurations  

## Getting Started

First, make sure the repo is up to date:
```sh
make sync
```
Start with the docker container by running the following command under the repo:
```sh
make shell
```
It may take long time to build the docker container for the first time. Once done, you should enter the docker container. To build the tool, run the following command:
```sh
cd /workspace
make build
```
This should also take long time to finish.

### Toy example
