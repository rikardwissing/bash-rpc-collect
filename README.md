# bash-rpc-collect

A simple bash script to save data from bitcoin (or any other similar coin) rpc calls.

## Usage

`collect /outputfolder /path/to/bitcoin-cli rpc-user rpc-password port`

Add it to cron for instance.

## RPC calls

```
getpeerinfo
getmininginfo
getconnectioncount
getmempoolinfo
getblockcount
getnetworkinfo
getnettotals
getdifficulty
getblockchaininfo
gettxoutsetinfo
getbestblockhash
getchaintips
getmemoryinfo
```

## Structure

### Latest
`/outputfolder/rpc-call/latest.json`

### Daily
`/outputfolder/rpc-call/daily/yymmdd.json`

### Hourly
`/outputfolder/rpc-call/hourly/yymmddhh.json`

## Current use

### Myriad
https://xmy-history.coinid.org/

#### Blockchain

https://xmy-history.coinid.org/getbestblockhash/latest.json

https://xmy-history.coinid.org/getblockcount/latest.json

https://xmy-history.coinid.org/getblockchaininfo/latest.json

https://xmy-history.coinid.org/getchaintips/latest.json

https://xmy-history.coinid.org/getdifficulty/latest.json

https://xmy-history.coinid.org/getmempoolinfo/latest.json

https://xmy-history.coinid.org/gettxoutsetinfo/latest.json

#### Control

https://xmy-history.coinid.org/getmemoryinfo/latest.json

#### Mining

https://xmy-history.coinid.org/getmininginfo/latest.json

#### Network

https://xmy-history.coinid.org/getconnectioncount/latest.json

https://xmy-history.coinid.org/getnetworkinfo/latest.json

https://xmy-history.coinid.org/getnettotals/latest.json

https://xmy-history.coinid.org/getpeerinfo/latest.json
