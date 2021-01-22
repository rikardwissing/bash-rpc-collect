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

