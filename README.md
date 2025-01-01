# 💜

## For verifying my signatures and commits

```console
curl -fs https://github.com/LiviaMedeiros.gpg | gpg --import
```
Or
```console
gpg --keyserver hkps://keys.openpgp.org --receive-keys 79CDDA8C485C57FF76CA43F8691C0F6AF4A67582
```

## For contacting and sending files to me securely

```console
gpg -ear "$(gpg --list-keys --with-colons 691C0F6AF4A67582 | grep '^uid:' | cut -d: -f10)" -o ENCRYPTED_MESSAGE YOUR_FILE
```


## For supporting me financially

  - BTC: `bc1qlz0azz0mq32mt3ja30gzd9h5t9tk4zzr207aqv`
  - LTC: `LNUNTsqG9S4PqQwqMPL5sD3ciPxNPS8CFd`
  - ETH: `0xB14ad0d9c20f083e90Ae9c14E6F231E6Fa1EE2A2`
  - USDT: `0xB14ad0d9c20f083e90Ae9c14E6F231E6Fa1EE2A2`
  - XMR: `46w6fcnMy4kdtxwLSxXZqYbVAHp4Cu47HPiQfzrqM761Qbj7xMJojmkEPhhc3jT98VDw746hgRQHgDh7RtHEnB3iSMu482T`
