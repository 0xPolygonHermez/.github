<div align="center">
<img src="Polygon_zkevm.png" width="600"/>
</div>
<br />
<div align="center">

[![Chat on Twitter][ico-twitter]][link-twitter]
[![Chat on Telegram][ico-telegram]][link-telegram]
[![Website][ico-website]][link-website]

</div>

[ico-twitter]: https://img.shields.io/twitter/url?label=polygonZkEVM&style=social&url=https%3A%2F%2Ftwitter.com%2F0xpolygonhermez
[ico-telegram]: https://img.shields.io/badge/telegram-telegram-black
[ico-website]: https://img.shields.io/static/v1?label=docs&message=polygonZkEVM&color=7B3FE4

[link-twitter]: https://twitter.com/0xpolygonhermez
[link-telegram]: https://t.me/polygonhermezchat
[link-website]: https://docs.hermez.io/


- `polygon zkEVM` is a ZK implementation of the Ethereum Virtual Machine (EVM).
- We aim to provide a decentralized Ethereum Layer 2 scalability solution utilising cryptographic zero-knowledge technology to provide validation and fast finality of off-chain transaction computations.
- Team has been working on the development of `polygon zkEVM` as a zero-knowledge Ethereum Virtual Machine (zkEVM), a virtual machine that executes Ethereum transactions in a transparent way, including smart contracts with zero-knowledge-proof validations.
- The approach taken requires the recreation of all EVM opcodes for transparent deployment of existing Ethereum smart contracts. For this purpose a new set of technologies and tools are being created and engineered and are contained in this organization.

## Ethereum compatibility
- The following table aims to summarize the zkEVM compatibility with the [oficial Ethereum test vectors](https://github.com/ethereum/tests)
- The test vectors targeted are located [here](https://github.com/ethereum/tests/tree/develop/BlockchainTests/GeneralStateTests)
- Detailed information could be found in the [zkevm-testvectors repository](https://github.com/0xPolygonHermez/zkevm-testvectors)

|             Folder Name              |  Total  | :heavy_check_mark: | :x: | Ignored | Coverage |
|:------------------------------------:|:-------:|:------------------:|:---:|:-------:|:--------:|
|         stArgsZeroOneBalance         | Pending |                    |     |         |          |
|             stAttackTest             | Pending |                    |     |         |          |
|             stBadOpcode              | Pending |                    |     |         |          |
|                stBugs                | Pending |                    |     |         |          |
|             stCallCodes              | Pending |                    |     |         |          |
|       stCallCreateCallCodeTest       | Pending |                    |     |         |          |
| stCallDelegateCodesCallCodeHomestead | Pending |                    |     |         |          |
|     stCallDelegateCodesHomestead     | Pending |                    |     |         |          |
|              stChainId               | Pending |                    |     |         |          |
|            stCodeCopyTest            | Pending |                    |     |         |          |
|           stCodeSizeLimit            | Pending |                    |     |         |          |
|              stCreate2               | Pending |                    |     |         |          |
|             stCreateTest             | Pending |                    |     |         |          |
|     stDelegatecallTestHomestead      | Pending |                    |     |         |          |
|           stEIP150Specific           | Pending |                    |     |         |          |
|     stEIP150singleCodeGasPrices      | Pending |                    |     |         |          |
|              stEIP1559               | Pending |                    |     |         |          |
|           stEIP158Specific           | Pending |                    |     |         |          |
|              stEIP2930               | Pending |                    |     |         |          |
|              stEIP3607               | Pending |                    |     |         |          |
|              stExample               | Pending |                    |     |         |          |
|            stExtCodeHash             | Pending |                    |     |         |          |
|         stHomesteadSpecific          | Pending |                    |     |         |          |
|            stInitCodeTest            | Pending |                    |     |         |          |
|              stLogTests              | Pending |                    |     |         |          |
|      stMemExpandingEIP150Calls       | Pending |                    |     |         |          |
|          stMemoryStressTest          | Pending |                    |     |         |          |
|             stMemoryTest             | Pending |                    |     |         |          |
|          stNonZeroCallsTest          | Pending |                    |     |         |          |
|        stPreCompiledContracts        | Pending |                    |     |         |          |
|       stPreCompiledContracts2        | Pending |                    |     |         |          |
|      stQuadraticComplexityTest       | Pending |                    |     |         |          |
|               stRandom               | Pending |                    |     |         |          |
|              stRandom2               | Pending |                    |     |         |          |
|          stRecursiveCreate           | Pending |                    |     |         |          |
|             stRefundTest             | Pending |                    |     |         |          |
|           stReturnDataTest           | Pending |                    |     |         |          |
|             stRevertTest             | Pending |                    |     |         |          |
|             stSLoadTest              | Pending |                    |     |         |          |
|             stSStoreTest             | Pending |                    |     |         |          |
|            stSelfBalance             | Pending |                    |     |         |          |
|               stShift                | Pending |                    |     |         |          |
|            stSolidityTest            | Pending |                    |     |         |          |
|            stSpecialTest             | Pending |                    |     |         |          |
|             stStackTests             | Pending |                    |     |         |          |
|             stStaticCall             | Pending |                    |     |         |          |
|         stStaticFlagEnabled          | Pending |                    |     |         |          |
|        stSystemOperationsTest        | Pending |                    |     |         |          |
|           stTimeConsuming            | Pending |                    |     |         |          |
|          stTransactionTest           | Pending |                    |     |         |          |
|           stTransitionTest           | Pending |                    |     |         |          |
|             stWalletTest             | Pending |                    |     |         |          |
|          stZeroCallsRevert           | Pending |                    |     |         |          |
|           stZeroCallsTest            | Pending |                    |     |         |          |
|           stZeroKnowledge            | Pending |                    |     |         |          |
|           stZeroKnowledge2           | Pending |                    |     |         |          |