# bitcoin:// URI generator
Just redirect to bitcoin:// URIs. Supports address and amount params. Web wersion also generates QR code with the URI inside.

## Params

* chain - specify the name of blockchain (it will the in the beginning of the URI: `bitcoin://...`
* address - recipient address 
* amount - tokens to send

## Example

If you want to send to `mvF1LyVR6yxFpEwmkeMVq3SBx2pX6mcFYV` 0.1 BTC, your link can be constructed like this:
```
https://flightwallet.org/pay/?address=mvF1LyVR6yxFpEwmkeMVq3SBx2pX6mcFYV&amount=0.1&chain=bitcoin
```

And you will be redirected to
```
bitcoin://mvF1LyVR6yxFpEwmkeMVq3SBx2pX6mcFYV?amount=0.1
```



_____
[*flightwallet*](https://flightwallet.org)

[<img src="https://raw.githubusercontent.com/morejust/foundation/master/madebymorejust.png" width="100">](https://morejust.foundation/?from=pravda.contracts)
