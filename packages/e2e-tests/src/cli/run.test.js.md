# Snapshot report for `src/cli/run.test.js`

The actual snapshot is saved in `run.test.js.snap`.

Generated by [AVA](https://ava.li).

## should create a new aragon app and run it successfully

> Snapshot 1

    `Start a local Ethereum network [started]␊
    Setting up a new chain from latest Aragon snapshot [started]␊
    Setting up a new chain from latest Aragon snapshot [completed]␊
    Starting a local chain from snapshot [started]␊
    Local chain started at port 8545 [title changed]␊
    Local chain started at port 8545 [completed]␊
    Start a local Ethereum network [completed]␊
    Check IPFS [started]␊
    Start IPFS [started]␊
    → Starting IPFS at port: 5001␊
    Start IPFS [completed]␊
    Add local files [started]␊
    Add local files [completed]␊
    Check IPFS [completed]␊
    Publish app to APM [started]␊
    Applying version bump (major) [started]␊
    Applying version bump (major) [completed]␊
    Deploy contract [started]␊
    Compile contracts [started]␊
    Compile contracts [completed]␊
    Deploy 'CounterApp' to network [started]␊
    → Deploying 'CounterApp' to network␊
    Deploy 'CounterApp' to network [completed]␊
    Generate deployment artifacts [started]␊
    Generate deployment artifacts [completed]␊
    Deploy contract [completed]␊
    Determine contract address for version [started]␊
    Determine contract address for version [completed]␊
    Building frontend [completed]␊
    Prepare files for publishing [started]␊
    Prepare files for publishing [completed]␊
    Generate application artifact [started]␊
    Generate application artifact [completed]␊
    Publish foobarfoo.open.aragonpm.eth [started]␊
    Generating transaction [started]␊
    → Fetching DAO at 0x9a348D0c3f55c2B3f6A400CC1BE71c882Ff1bdC3...␊
    Generating transaction [completed]␊
    Sending transaction [started]␊
    → Waiting for transaction to be mined...␊
    Sending transaction [completed]␊
    Publish foobarfoo.open.aragonpm.eth [completed]␊
    Fetch published repo [started]␊
    Fetch published repo [completed]␊
    Publish app to APM [completed]␊
    Create DAO [started]␊
    Fetching template bare-kit.aragonpm.eth@latest [started]␊
    Fetching template bare-kit.aragonpm.eth@latest [completed]␊
    Create new DAO from template [started]␊
    Create new DAO from template [completed]␊
    Checking DAO [started]␊
    Checking DAO [completed]␊
    Create DAO [completed]␊
    Open DAO [started]␊
    Starting Aragon client [started]␊
    → Starting Aragon client...␊
    Starting Aragon client [completed]␊
    Opening wrapper [started]␊
    → Opening wrapper␊
    Opening wrapper [completed]␊
    Open DAO [completed]␊
     i You are now ready to open your app in Aragon.␊
     i Here are some Ethereum accounts you can use.␊
      The first one will be used for all the actions the CLI performs.␊
      You can use your favorite Ethereum provider or wallet to import their private keys.␊
      ␊
    Address #1:  0xb4124cEB3451635DAcedd11767f004d8a28c6eE7 (this account is used to deploy DAOs, it has more permissions)␊
    Private key: a8a54b2d8197bc0b19bb8a084031be71835580a01e70a45a13babd16c9bc1563␊
    Address #2:  0x8401Eb5ff34cc943f096A32EF3d5113FEbE8D4Eb ␊
    Private key: ce8e3bda3b44269c147747a373646393b1504bfcbb73fc9564f5d753d8116608␊
     i The accounts were generated from the following mnemonic phrase:␊
    explain tackle mirror kit van hammer degree position ginger unfair soup bonus␊
    ␊
     ⚠ The devchain was reset, some steps need to be done to prevent issues:␊
        - Reset the application cache in Aragon Core by going to Settings > Troubleshooting.␊
        - If using Metamask: switch to a different network, and then switch back to the 'Private Network' (this will clear the nonce cache and prevent errors when sending transactions)  ␊
      ␊
    ␊
     i This is the configuration for your development deployment:␊
        Ethereum Node: ws://localhost:8545␊
        ENS registry: 0x5f6f7e8cc7346a11ca2def8f827b7a0b612c56a1␊
        APM registry: open.aragonpm.eth␊
        DAO address: 0xe5ac265B0FFE4b47C8386D7d715f3a3f6F8fb5B9␊
    ␊
        Opening http://localhost:3000/#/0xe5ac265B0FFE4b47C8386D7d715f3a3f6F8fb5B9 to view your DAO`

> Snapshot 2

    200

> Snapshot 3

    `<!DOCTYPE html>␊
    <html lang="en">␊
      <head>␊
        <meta charset="utf-8">␊
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no, maximum-scale=1, user-scalable=no">␊
        <link rel="shortcut icon" type="image/svg+xml" href="/favicon.caf9c731.svg">␊
        <link rel="shortcut icon" type="image/png" href="/favicon.6d47dbe5.png">␊
        <title>Aragon</title>␊
        <style>html, body {␊
            height: 100%;␊
            overflow: hidden;␊
          }</style>␊
      </head>␊
      <body>␊
        <noscript>␊
          You need to enable JavaScript to run this app.␊
        </noscript>␊
        <div id="root"></div>␊
        <script src="/src.e31bb0bc.js"></script>␊
      </body>␊
    </html>␊
    `
