Nodium Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/PIVX-Project/PIVX.svg?branch=master)](https://travis-ci.org/PIVX-Project/PIVX) [![GitHub version](https://badge.fury.io/gh/PIVX-Project%2FPIVX.svg)](https://badge.fury.io/gh/PIVX-Project%2FPIVX)

Nodium is an open source crypto-currency focused on fast private transactions with low transaction fees & environmental footprint.  It utilizes a custom Proof of Stake protocol for securing its network and uses an innovative variable seesaw reward mechanism that dynamically balances 90% of its block reward size between masternodes and staking nodes and 10% dedicated for staking. 
- Anonymized transactions using Privatesend.
- Fast transactions featuring guaranteed zero confirmation transactions using SwiftNode.

More information at [nodium.org](http://www.nodium.org)

### Coin Specs
<table>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoW Phase)</td><td>49,750 XN</td></tr>
<tr><td>Max Coin Supply (PoS Phase, Pre Infinite)</td><td>29,259,115 XN</td></tr>
<tr><td>Premine</td><td>4,000,000 XN*</td></tr>
<tr><td>Premine burn</td><td>1,000,000 XN*</td></tr>
<tr><td>Block maturity</td><td>60 minutes</td></tr>
</table>

### PoW Rewards Breakdown

<table>
<th>Block Height</th><th>Masternodes</th><th>Miner</th>
<tr><td>2-200</td><td>90% (225 XN)</td><td>10% (25 XN)</td></tr>
</table>

### PoS Rewards Breakdown

<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Masternode</th><th>Staking</th>
<tr><td>Phase 1</td><td>201-50000</td><td>200 XN</td><td>90% (180 XN)</td><td>10%</td></tr>
<tr><td>Phase 2</td><td>50001-75000</td><td>150 XN</td><td>90% (135 XN)</td><td>10%</td></tr>
<tr><td>Phase 3</td><td>75001-100000</td><td>100 XN</td><td>90% (90 XN)</td><td>10%</td></tr>
<tr><td>Phase 4</td><td>100001-150000</td><td>75 XN</td><td>90% (67.5 XN)</td><td>10%</td></tr>
<tr><td>Phase 5</td><td>150001-200000</td><td>50 XN</td><td>90% (45 XN)</td><td>10%</td></tr>
<tr><td>Phase 6</td><td>200001-250000</td><td>30 XN</td><td>90% (27 XN)</td><td>10%</td></tr>
<tr><td>Phase 7</td><td>250001-300000</td><td>15 XN</td><td>90% (13.5 XN)</td><td>10%</td></tr>
<tr><td>Phase 8</td><td>300001-400000</td><td>10 XN</td><td>90% (9 XN)</td><td>10%</td></tr>
<tr><td>Phase 9</td><td>400001-500000</td><td>5 XN</td><td>90% (4.5 XN)</td><td>10%</td></tr>
<tr><td>Phase X</td><td>500001-Infinite</td><td>5 XN</td><td>90% (4.5 XN)</td><td>10%</td></tr>
</table>
