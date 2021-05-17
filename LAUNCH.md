How to launch your own token:

1. Buy atleast 200KB RAM from protonresources.com
2. Download proton.token ABI and WASM from https://github.com/ProtonProtocol/proton.token/tree/main/contracts/proton.token
3. Log in at https://proton.bloks.io/wallet/utilities/upload-contract and upload the code and ABI

For the next few steps, replace tokentester in all URLs and parameters with your own account name

4. Go to https://proton.bloks.io/account/tokentester?loadContract=true&tab=Actions&account=tokentester&scope=tokentester&limit=100&action=create

issuer: is "tokentester"
maximum_supply: is the maximum # that can ever be minted of your token e.g. 1000000.0000 MEME, notice the .0000 means a precision of 4 decimals

5. Go to https://proton.bloks.io/account/tokentester?loadContract=true&tab=Actions&account=tokentester&scope=tokentester&limit=100&action=issue

to: is "tokentester"
quantity: is how much you want to issue right now, e.g. 4.0000 MEME
memo: you can leave empty

Then the token should appear in your wallet 🙂