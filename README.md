# Ft_onion

Introductory project allowing the implementation of a hidden service on tor.

The goal of this project is to create a web page and make it accessible from the Tor network by creating a hidden service. The hidden service is a web service that hides on the Tor network.
What is the Tor network?

## Usage
```sh
sudo apt update
sudo apt install git make docker.io
```
```sh
echo "USR_PASS=exemple" > .env
mkdir ssh && cp ~/.ssh/id_rsa.pub ssh/authorized_keys
```
```sh
git clone git@github.com:Skalyaeve/ft_onion.git
cd ft_onion
sudo make # then browse to http://localhost:8383
```
```sh
sudo make stop
sudo make fclean
```
