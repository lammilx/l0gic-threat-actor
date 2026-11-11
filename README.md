# THREAT ACTOR ANALYSIS
 Public IOC collection and threat actor notes
-----------------------------------------------
---

## Actor: "logic" (l0gic)

- **Alias:** logic, l0gic
- **Affiliation:** The Community
- **Type:** Solo operator — botnet herder, malware developer, and data distributor 
- **First observed:** 2022-23?
- **Status:** Active

### Overview

"logic" (also styled l0gic) is a solo threat actor operating within
The Community — a decentralized collective of botnet operators and
malware developers.

- recently got into data distribution

## Known Groups:
- b0v (board 0f violence) : a group that focuses on stolen data and distribution of stolen data
- INSR (insurgence) : recently found out, not much known/researched

### Tooling

| Name          | Type                | Notes                                    |
|---------------|---------------------|------------------------------------------|
| l0gicLoader   | Modular loader      | Initial payload delivery, AV evasion     |
| l0gicBot      | Botnet client       | DDoS, credential harvest, RCE            |
| l0gicStealer  | Infostealer         | Browser creds, session tokens, wallets   |
and other niche tooling!

written: 7/10/26
