## Create Bitsong Validator

Useful links:

- Official documentation [https://docs.bitsong.io/blockchain/join-the-mainnet]<br />
- Bitsong Wallet [https://wallet.bitsong.io/]<br />

## Install go oneline-command

```
wget https://go.dev/dl/go1.18.3.linux-amd64.tar.gz && sudo tar -C /usr/local -xzf go1.18.3.linux-amd64.tar.gz && mkdir -p $HOME/go/bin && PATH=$PATH:/usr/local/go/bin && echo "export PATH=$PATH:$(go env GOPATH)/bin" >> ~/.bash_profile && source ~/.bash_profile && go version
```
## Install bitsong node oneline-command

```
cd $HOME && git clone https://github.com/bitsongofficial/go-bitsong && cd go-bitsong && git checkout v0.10.0 && make install
```

