# FAQ

## The `masternode outputs` return an empty object.
```
{
}
```

You must receive the **10000 PIVX** for the **masternode** in a single transaction on your **Control Wallet** and wait for at least 1 confirmation.
> If you already have the **10000 PIVX** but it came from multiple transactions, you can send the **10000 PIVX** back to yourself:
```
docker exec pivx-wallet pivx-cli sendfrom "" YoUrAdDr3Ss PIVX
```

## Running a **wallet** or a **masternode** container result in the following error:
```
No such file or directory
```

Ensure the `data` folder is *writable* for the container.
