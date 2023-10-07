# Faucet

```
{
    "addr": "0xd9e5c94a12f78a96640757ac97ba0c257e8aa262",
    "privateKey": "0xcb9db6b5878db2fa20586e23b7f7b51c22a7c6ed0530daafc2615b116f170cd3",
    "publicKey": "0xe457895cab717434de97fee000c75e4f814472d89e351c72f537e909d051593522989b7d734fa9479c54450ff3c34279e85c9c883b04d443e50873211ed43f88"
}
```



# How to get funds

- add network `eth network:add mw-evm --url https://evm.pilou.dev/ --id 1337`
- create an evm address `eth address:random`
- register address `eth address:add myaddr <generated pk>`
- add faucet `eth address:add faucet 0xcb9db6b5878db2fa20586e23b7f7b51c22a7c6ed0530daafc2615b116f170cd3`
- get 100 eth from faucet: `eth transaction:send --pk faucet --to myaddr --value 100000000000000000000 -n mw-evm`
- rw: amounts are usually in wei, and 10^18 wei = 1 eth

# prez
https://hackmd.io/@p-ec/BkB4VRRxa

# tools

- eth-cli : https://www.npmjs.com/package/eth-cli `npm install -g eth-cli`
- metamask
-