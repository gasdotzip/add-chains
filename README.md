<p align="center">
 <img width="100px" src="https://www.gas.zip/gasLogo400x400.png" align="center" />
 <h3 align="center">Gas.zip Global Chain List</h3>
</p>


# Global Chain List

At Gas.zip we strive to integrate and support nearly any and all chains that are in demand. With dozens of reference points online for discovering new chains, we can't stay atop of them all. By open sourcing our global chain list, we hope contributors and ecosystem members will assist in adding new and desirable mainnet and testnet chains as soon as they become available. 


## Submitting a Chain

All chains not in the production chainlist folder are eligible for submission. This does **not** mean that the chain is guaranteed to be added to Gas.zip. We will take in and assess every chain submitted, and users who submit chains that go on to be deemed desirable and sufficient enough to be added to Gas.zip will receive contribution points. 

## Submission Template

Your chainID.json should have, at minimum, the following: 

<b>chainID.json</b>: 
```
{
    "chainId": "",
    "rpcs": [],
    "name": "",
    "symbol": "",
    "mainnet": ,
    "address": "",
    "explorer": ""
}
```
Your PR should additionally have the following inline, but **not** in the chains.json: 

**Website:** 

**Chain Logo:**

**Bridge:**

## Submission Tips

For the highest quality submission and highest chance of being added, please consider the following: 

| Field | Requirements |
|-------|-------------|
| chainID | Formal chainID. |
| rpcs | Public RPCs, ideally as many as possible. |
| name | Formal chain name (including X Sepolia, X Testnet). |
| symbol | Canonical tokens symbol or ticker (the chain's gas token). |
| mainnet | True or false. |
| address | EVM, SVM, MOVE, or INIT. |
| explorer | Explorer URL, active and working. |
| Website | Formal project website. |
| Chain Logo | Ideally, a 400 x 400 SVG. PNGs acceptable. |
| Bridge | The canonical bridge or the primary method of bridging.|

## Contribution Points

Users who contribute chains will receive points (updated weekly) on the contributions list, for either submission for submission and integration (if Gas.zip results in adding the chain as well). 