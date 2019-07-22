## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| ethereum/contracts/BTCCurrency.sol | 078298ff19c89d40ede080ec0b01c5bb6dc151ef |
| ethereum/contracts/Currency.sol | f76dfbdf849e14202af874b7a3e96e244775de6d |
| ethereum/contracts/DSMath.sol | 2a06c744883278ceb39e54b558395359454e519f |
| ethereum/contracts/Funds.sol | a2de9e98ee0679061b795f8146aeaf0a48a43d26 |
| ethereum/contracts/Loans.sol | 72400480e986cbf206ef249bd14aca6c28833df3 |
| ethereum/contracts/Medianizer.sol | 31888451070ff075b4d7fa3d30fc0177a2bd4cfc |
| ethereum/contracts/Migrations.sol | e8fc04f294cacc963593a12ee2c73058f6d1128a |
| ethereum/contracts/Sales.sol | 7df226f3d981a115f8447f6ebede989399182649 |
| ethereum/contracts/Vars.sol | 1c558537bd6bd640b03676044787d53759ddb8c5 |
| oracles/contracts/Buffer.sol | c9279716c2b0411f919d07b5803b1ecae38cc8f5 |
| oracles/contracts/DSMath.sol | c7251d9017d4ed859e91bcef45d4f5c1f454de03 |
| oracles/contracts/DSValue.sol | a2f3f9f730319355c782053c04886e47138f76b6 |
| oracles/contracts/ERC20.sol | 45b7754c1112312c37054ab2fab1e71bd27fb3b4 |
| oracles/contracts/Medianizer.sol | 6b1f2ad14ed66e137f194fde19158b15145a9ac6 |
| oracles/contracts/Migrations.sol | e61057a352ae8d823d9a67ba231bed8a3017626f |
| oracles/contracts/Oracle.sol | 44d0e4aacb2b65e0b194511a90cf4f4a5a881ee0 |
| oracles/contracts/WETH.sol | ebc95c26a2aa6d8a07d2a96a028cea97c297bd04 |
| oracles/contracts/WETH9.sol | ee3e6250a8886a1d9327acb960fd444b0e379d47 |
| oracles/contracts/chainlink/BlockchainInfo.sol | 56a6c98001f1a28db4ad4a4e6c363a78f06f5957 |
| oracles/contracts/chainlink/ChainLink.sol | 44fc5b7893b21b7872598c8052e7af7d3b7c9598 |
| oracles/contracts/chainlink/CoinMarketCap.sol | 278b8e73b10cf7b649625fbbf6663deb7ed14d93 |
| oracles/contracts/chainlink/CryptoCompare.sol | 0d78da1b5fab6e444b6e1bc7166fa09fa1b9a448 |
| oracles/contracts/chainlink/Gemini.sol | 9d608b02ede70feb35b8e178a331b801dd52a5ce |
| oracles/contracts/chainlink/SoChain.sol | b52b37dcc135a4ec8ef6f7e6ce0c1b83f351287a |
| oracles/contracts/oraclize/Bitstamp.sol | 95fa36649693685ac78fa52cd0ad3a3c3695f645 |
| oracles/contracts/oraclize/Coinbase.sol | db5baacebaf3fd36e966e95dee7022bdf9c56fa2 |
| oracles/contracts/oraclize/Coinpaprika.sol | c0d8a92558690d8b041ce26dff28a26ee2b81d74 |
| oracles/contracts/oraclize/CryptoWatch.sol | 1c49d7c049855f4736a077c4e9b443f6e225d0e3 |
| oracles/contracts/oraclize/Kraken.sol | 001df0bdcda5f095ddb3844ebafcdb0c1c2b22b8 |
| oracles/contracts/oraclize/Oraclize.sol | c2da807c0fc1c6ab9a9db2fa45954cd0bbff1d1c |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **BTCCurrency** | Implementation | DSMath |||
| └ | cmul | Public ❗️ |   |NO❗️ |
| └ | cdiv | Public ❗️ |   |NO❗️ |
||||||
| **Currency** | Implementation |  |||
| └ | COL | Public ❗️ | 🛑  |NO❗️ |
| └ | name | Public ❗️ | 🛑  |NO❗️ |
| └ | cmul | Public ❗️ |   |NO❗️ |
| └ | cdiv | Public ❗️ |   |NO❗️ |
||||||
| **DSMath** | Implementation |  |||
| └ | add | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | mul | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | min | Internal 🔒 |   | |
| └ | max | Internal 🔒 |   | |
| └ | imin | Internal 🔒 |   | |
| └ | imax | Internal 🔒 |   | |
| └ | wmul | Internal 🔒 |   | |
| └ | rmul | Internal 🔒 |   | |
| └ | wdiv | Internal 🔒 |   | |
| └ | rdiv | Internal 🔒 |   | |
| └ | rpow | Internal 🔒 |   | |
||||||
| **Funds** | Implementation | DSMath |||
| └ | setLoans | Public ❗️ | 🛑  |NO❗️ |
| └ | own | Public ❗️ |   |NO❗️ |
| └ | mila | Public ❗️ |   |NO❗️ |
| └ | mala | Public ❗️ |   |NO❗️ |
| └ | mild | Public ❗️ |   |NO❗️ |
| └ | mald | Public ❗️ |   |NO❗️ |
| └ | lint | Public ❗️ |   |NO❗️ |
| └ | lpen | Public ❗️ |   |NO❗️ |
| └ | lfee | Public ❗️ |   |NO❗️ |
| └ | rat | Public ❗️ |   |NO❗️ |
| └ | agent | Public ❗️ |   |NO❗️ |
| └ | bal | Public ❗️ |   |NO❗️ |
| └ | tok | Public ❗️ |   |NO❗️ |
| └ | cur | Public ❗️ |   |NO❗️ |
| └ | vars | Public ❗️ |   |NO❗️ |
| └ | open | Public ❗️ | 🛑  |NO❗️ |
| └ | push | Public ❗️ | 🛑  |NO❗️ |
| └ | gen | Public ❗️ | 🛑  |NO❗️ |
| └ | set | Public ❗️ | 🛑  |NO❗️ |
| └ | set | Public ❗️ | 🛑  |NO❗️ |
| └ | req | Public ❗️ | 🛑  |NO❗️ |
| └ | pull | Public ❗️ | 🛑  |NO❗️ |
| └ | calc | Public ❗️ |   |NO❗️ |
| └ | lopen | Private 🔐 | 🛑  | |
| └ | lsech | Private 🔐 | 🛑  | |
| └ | gsech | Private 🔐 |   | |
||||||
| **Loans** | Implementation | DSMath |||
| └ | bor | Public ❗️ |   |NO❗️ |
| └ | lend | Public ❗️ |   |NO❗️ |
| └ | agent | Public ❗️ |   |NO❗️ |
| └ | apex | Public ❗️ | 🛑  |NO❗️ |
| └ | acex | Public ❗️ | 🛑  |NO❗️ |
| └ | biex | Public ❗️ | 🛑  |NO❗️ |
| └ | prin | Public ❗️ |   |NO❗️ |
| └ | lint | Public ❗️ |   |NO❗️ |
| └ | lfee | Public ❗️ |   |NO❗️ |
| └ | lpen | Public ❗️ |   |NO❗️ |
| └ | col | Public ❗️ |   |NO❗️ |
| └ | back | Public ❗️ |   |NO❗️ |
| └ | rat | Public ❗️ |   |NO❗️ |
| └ | lent | Public ❗️ |   |NO❗️ |
| └ | lentb | Public ❗️ |   |NO❗️ |
| └ | owed | Public ❗️ |   |NO❗️ |
| └ | owedb | Public ❗️ |   |NO❗️ |
| └ | dedu | Public ❗️ |   |NO❗️ |
| └ | dedub | Public ❗️ |   |NO❗️ |
| └ | pushed | Public ❗️ |   |NO❗️ |
| └ | marked | Public ❗️ |   |NO❗️ |
| └ | taken | Public ❗️ |   |NO❗️ |
| └ | sale | Public ❗️ |   |NO❗️ |
| └ | paid | Public ❗️ |   |NO❗️ |
| └ | off | Public ❗️ |   |NO❗️ |
| └ | colv | Public ❗️ | 🛑  |NO❗️ |
| └ | min | Public ❗️ |   |NO❗️ |
| └ | safe | Public ❗️ | 🛑  |NO❗️ |
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | setSales | Public ❗️ | 🛑  |NO❗️ |
| └ | open | Public ❗️ | 🛑  |NO❗️ |
| └ | setSechs | Public ❗️ | 🛑  |NO❗️ |
| └ | push | Public ❗️ | 🛑  |NO❗️ |
| └ | mark | Public ❗️ | 🛑  |NO❗️ |
| └ | take | Public ❗️ | 🛑  |NO❗️ |
| └ | pay | Public ❗️ | 🛑  |NO❗️ |
| └ | unpay | Public ❗️ | 🛑  |NO❗️ |
| └ | pull | Public ❗️ | 🛑  |NO❗️ |
| └ | pull | Public ❗️ | 🛑  |NO❗️ |
| └ | sechi | Private 🔐 |   | |
| └ | sell | Public ❗️ | 🛑  |NO❗️ |
||||||
| **Medianizer** | Implementation |  |||
| └ | peek | Public ❗️ | 🛑  |NO❗️ |
| └ | read | Public ❗️ | 🛑  |NO❗️ |
| └ | poke | Public ❗️ | 🛑  |NO❗️ |
| └ | void | Public ❗️ | 🛑  |NO❗️ |
| └ | push | Public ❗️ | 🛑  |NO❗️ |
||||||
| **Migrations** | Implementation |  |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | setCompleted | Public ❗️ | 🛑  | restricted |
| └ | upgrade | Public ❗️ | 🛑  | restricted |
||||||
| **Sales** | Implementation | DSMath |||
| └ | bid | Public ❗️ | 🛑  |NO❗️ |
| └ | bidr | Public ❗️ | 🛑  |NO❗️ |
| └ | bor | Public ❗️ | 🛑  |NO❗️ |
| └ | lend | Public ❗️ | 🛑  |NO❗️ |
| └ | agent | Public ❗️ | 🛑  |NO❗️ |
| └ | salex | Public ❗️ | 🛑  |NO❗️ |
| └ | setex | Public ❗️ | 🛑  |NO❗️ |
| └ | pbkh | Public ❗️ | 🛑  |NO❗️ |
| └ | taken | Public ❗️ | 🛑  |NO❗️ |
| └ | off | Public ❗️ | 🛑  |NO❗️ |
| └ | sechA | Public ❗️ | 🛑  |NO❗️ |
| └ | secA | Public ❗️ | 🛑  |NO❗️ |
| └ | sechB | Public ❗️ | 🛑  |NO❗️ |
| └ | secB | Public ❗️ | 🛑  |NO❗️ |
| └ | sechC | Public ❗️ | 🛑  |NO❗️ |
| └ | secC | Public ❗️ | 🛑  |NO❗️ |
| └ | sechD | Public ❗️ | 🛑  |NO❗️ |
| └ | secD | Public ❗️ | 🛑  |NO❗️ |
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | next | Public ❗️ |   |NO❗️ |
| └ | open | Public ❗️ | 🛑  |NO❗️ |
| └ | push | Public ❗️ | 🛑  |NO❗️ |
| └ | sign | Public ❗️ | 🛑  |NO❗️ |
| └ | sec | Public ❗️ | 🛑  |NO❗️ |
| └ | hasSecs | Public ❗️ |   |NO❗️ |
| └ | take | Public ❗️ | 🛑  |NO❗️ |
| └ | unpush | Public ❗️ | 🛑  |NO❗️ |
||||||
| **Vars** | Implementation |  |||
| └ | APEXT | Public ❗️ | 🛑  |NO❗️ |
| └ | ACEXT | Public ❗️ | 🛑  |NO❗️ |
| └ | BIEXT | Public ❗️ | 🛑  |NO❗️ |
| └ | SALEX | Public ❗️ | 🛑  |NO❗️ |
| └ | SETEX | Public ❗️ | 🛑  |NO❗️ |
| └ | MINBI | Public ❗️ | 🛑  |NO❗️ |
||||||
| **Buffer** | Library |  |||
| └ | init | Internal 🔒 |   | |
| └ | fromBytes | Internal 🔒 |   | |
| └ | resize | Private 🔐 |   | |
| └ | max | Private 🔐 |   | |
| └ | truncate | Internal 🔒 |   | |
| └ | write | Internal 🔒 |   | |
| └ | append | Internal 🔒 |   | |
| └ | append | Internal 🔒 |   | |
| └ | writeUint8 | Internal 🔒 |   | |
| └ | appendUint8 | Internal 🔒 |   | |
| └ | write | Private 🔐 |   | |
| └ | writeBytes20 | Internal 🔒 |   | |
| └ | appendBytes20 | Internal 🔒 |   | |
| └ | appendBytes32 | Internal 🔒 |   | |
| └ | writeInt | Private 🔐 |   | |
| └ | appendInt | Internal 🔒 |   | |
||||||
| **CBOR** | Library |  |||
| └ | encodeType | Private 🔐 |   | |
| └ | encodeIndefiniteLengthType | Private 🔐 |   | |
| └ | encodeUInt | Internal 🔒 |   | |
| └ | encodeInt | Internal 🔒 |   | |
| └ | encodeBytes | Internal 🔒 |   | |
| └ | encodeString | Internal 🔒 |   | |
| └ | startArray | Internal 🔒 |   | |
| └ | startMap | Internal 🔒 |   | |
| └ | endSequence | Internal 🔒 |   | |
||||||
| **DSMath** | Implementation |  |||
| └ | add | Internal 🔒 |   | |
| └ | sub | Internal 🔒 |   | |
| └ | mul | Internal 🔒 |   | |
| └ | div | Internal 🔒 |   | |
| └ | min | Internal 🔒 |   | |
| └ | max | Internal 🔒 |   | |
| └ | hadd | Internal 🔒 |   | |
| └ | hsub | Internal 🔒 |   | |
| └ | hmul | Internal 🔒 |   | |
| └ | hdiv | Internal 🔒 |   | |
| └ | hmin | Internal 🔒 |   | |
| └ | hmax | Internal 🔒 |   | |
| └ | imin | Internal 🔒 |   | |
| └ | imax | Internal 🔒 |   | |
| └ | wadd | Internal 🔒 |   | |
| └ | wsub | Internal 🔒 |   | |
| └ | wmul | Internal 🔒 |   | |
| └ | wdiv | Internal 🔒 |   | |
| └ | wmin | Internal 🔒 |   | |
| └ | wmax | Internal 🔒 |   | |
| └ | radd | Internal 🔒 |   | |
| └ | rsub | Internal 🔒 |   | |
| └ | rmul | Internal 🔒 |   | |
| └ | rdiv | Internal 🔒 |   | |
| └ | rpow | Internal 🔒 |   | |
| └ | rmin | Internal 🔒 |   | |
| └ | rmax | Internal 🔒 |   | |
| └ | cast | Internal 🔒 |   | |
||||||
| **DSValue** | Implementation | DSMath |||
| └ | peek | Public ❗️ |   |NO❗️ |
| └ | read | Public ❗️ |   |NO❗️ |
| └ | poke | Public ❗️ | 🛑  |NO❗️ |
| └ | setMax | Public ❗️ | 🛑  |NO❗️ |
||||||
| **ERC20Basic** | Implementation |  |||
| └ | balanceOf | Public ❗️ |   |NO❗️ |
| └ | transfer | Public ❗️ | 🛑  |NO❗️ |
||||||
| **ERC20** | Implementation | ERC20Basic |||
| └ | allowance | Public ❗️ |   |NO❗️ |
| └ | transferFrom | Public ❗️ | 🛑  |NO❗️ |
| └ | approve | Public ❗️ | 🛑  |NO❗️ |
||||||
| **Medianizer** | Implementation | DSValue |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | set | Public ❗️ | 🛑  |NO❗️ |
| └ | set | Internal 🔒 | 🛑  | |
| └ | set | Internal 🔒 | 🛑  | |
| └ | setMax | Public ❗️ | 🛑  |NO❗️ |
| └ | push | Public ❗️ | 🛑  |NO❗️ |
| └ | poke | Public ❗️ | 🛑  |NO❗️ |
| └ | poke | Public ❗️ | 🛑  |NO❗️ |
| └ | compute | Public ❗️ |   |NO❗️ |
||||||
| **Migrations** | Implementation |  |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | setCompleted | Public ❗️ | 🛑  | restricted |
| └ | upgrade | Public ❗️ | 🛑  | restricted |
||||||
| **Oracle** | Implementation | DSMath |||
| └ | peek | Public ❗️ |   |NO❗️ |
| └ | read | Public ❗️ |   |NO❗️ |
| └ | eval | Public ❗️ |   |NO❗️ |
| └ | push | Public ❗️ | 🛑  |NO❗️ |
| └ | bill | Public ❗️ |   |NO❗️ |
| └ | pack | Public ❗️ | 🛑  |NO❗️ |
| └ | pack | Public ❗️ | 🛑  |NO❗️ |
| └ | call | Internal 🔒 | 🛑  | |
| └ | chec | Internal 🔒 | 🛑  | |
| └ | post | Internal 🔒 | 🛑  | |
| └ | tell | Internal 🔒 | 🛑  | |
| └ | ward | Internal 🔒 | 🛑  | |
||||||
| **WETH** | Implementation | ERC20 |||
| └ | deposit | Public ❗️ |  💵 |NO❗️ |
| └ | withdraw | Public ❗️ | 🛑  |NO❗️ |
||||||
| **WETH9** | Implementation |  |||
| └ | \<Fallback\> | Public ❗️ |  💵 |NO❗️ |
| └ | deposit | Public ❗️ |  💵 |NO❗️ |
| └ | withdraw | Public ❗️ | 🛑  |NO❗️ |
| └ | totalSupply | Public ❗️ |   |NO❗️ |
| └ | approve | Public ❗️ | 🛑  |NO❗️ |
| └ | transfer | Public ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | Public ❗️ | 🛑  |NO❗️ |
||||||
| **BlockchainInfo** | Implementation | ChainLink |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | ChainLink |
| └ | call | Internal 🔒 | 🛑  | |
| └ | chec | Internal 🔒 | 🛑  | |
||||||
| **ChainLink** | Implementation | ChainlinkClient, Oracle |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | pack | Public ❗️ | 🛑  |NO❗️ |
| └ | call | Internal 🔒 | 🛑  | |
| └ | chec | Internal 🔒 | 🛑  | |
| └ | cur | Public ❗️ | 🛑  | recordChainlinkFulfillment |
| └ | sup | Public ❗️ | 🛑  | recordChainlinkFulfillment |
| └ | ward | Internal 🔒 | 🛑  | |
| └ | setMax | Public ❗️ | 🛑  |NO❗️ |
||||||
| **CoinMarketCap** | Implementation | ChainLink |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | ChainLink |
| └ | call | Internal 🔒 | 🛑  | |
| └ | chec | Internal 🔒 | 🛑  | |
||||||
| **CryptoCompare** | Implementation | ChainLink |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | ChainLink |
| └ | call | Internal 🔒 | 🛑  | |
| └ | chec | Internal 🔒 | 🛑  | |
||||||
| **Gemini** | Implementation | ChainLink |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | ChainLink |
| └ | call | Internal 🔒 | 🛑  | |
| └ | chec | Internal 🔒 | 🛑  | |
||||||
| **SoChain** | Implementation | ChainLink |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | ChainLink |
| └ | call | Internal 🔒 | 🛑  | |
| └ | chec | Internal 🔒 | 🛑  | |
||||||
| **Bitstamp** | Implementation | Oraclize |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | Oraclize |
| └ | call | Internal 🔒 | 🛑  | |
||||||
| **Coinbase** | Implementation | Oraclize |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | Oraclize |
| └ | call | Internal 🔒 | 🛑  | |
||||||
| **Coinpaprika** | Implementation | Oraclize |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | Oraclize |
| └ | call | Internal 🔒 | 🛑  | |
||||||
| **CryptoWatch** | Implementation | Oraclize |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | Oraclize |
| └ | call | Internal 🔒 | 🛑  | |
||||||
| **Kraken** | Implementation | Oraclize |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | Oraclize |
| └ | call | Internal 🔒 | 🛑  | |
||||||
| **Oraclize** | Implementation | usingOraclize, Oracle |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | \<Fallback\> | Public ❗️ |  💵 |NO❗️ |
| └ | bill | Public ❗️ |   |NO❗️ |
| └ | pack | Public ❗️ | 🛑  |NO❗️ |
| └ | pack | Public ❗️ | 🛑  |NO❗️ |
| └ | __callback | Public ❗️ | 🛑  |NO❗️ |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
