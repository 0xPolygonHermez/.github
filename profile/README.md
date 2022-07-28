<div align="center">
<img src="https://github.com/0xPolygonHermez/.github/blob/master/profile/Polygon_zkevm.png" width="600"/>
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


- `polygon zkEVM` is a new zk-rollup that provides Ethereum Virtual Machine (EVM) equivalence (opcode-level compatibility) for a transparent user experience and existing Ethereum ecosystem and tooling compatibility.
- It consists on a decentralized Ethereum Layer 2 scalability solution utilising cryptographic zero-knowledge technology to provide validation and fast finality of off-chain transaction computations.
- This approach required the recreation of all EVM opcodes for transparent deployment and transactions with existing Ethereum smart contracts. For this purpose a new set of tools and technologies were created and engineered and are contained in this organization.

## Ethereum compatibility
- The following table aims to summarize the zkEVM compatibility with the [official Ethereum test vectors](https://github.com/ethereum/tests)
- The test vectors targeted are located [here](https://github.com/ethereum/tests/tree/develop/BlockchainTests/GeneralStateTests)
- Detailed information could be found in the [zkevm-testvectors repository](https://github.com/0xPolygonHermez/zkevm-testvectors)

|             Folder Name              |  Total  | :heavy_check_mark: | :x: | Ignored | Coverage |
|:------------------------------------:|:-------:|:------------------:|:---:|:-------:|:--------:|
|         stArgsZeroOneBalance         | Pending |                    |     |         |          |
|             stAttackTest             | Pending |                    |     |         |          |
|             stBadOpcode              | 320 |    129                |  191   |         |    40%      |
|                stBugs                | Pending |                    |     |         |          |
|             stCallCodes              | 87 |        53            |  16   |         |      61%    |
|       stCallCreateCallCodeTest       | Pending |                    |     |         |          |
| stCallDelegateCodesCallCodeHomestead | 58 |     34               |  24   |         |     59%     |
|     stCallDelegateCodesHomestead     | 58 |     37               |  21   |         |     64%     |
|              stChainId               | Pending |                    |     |         |          |
|            stCodeCopyTest            | 2 |       2             |  0   |         |   100%       |
|           stCodeSizeLimit            | Pending |                    |     |         |          |
|              stCreate2               | Pending |                    |     |         |          |
|             stCreateTest             | 101 |     65               |  36   |         |    64%      |
|     stDelegatecallTestHomestead      | Pending |                    |     |         |          |
|           stEIP150Specific           | Pending |                    |     |         |          |
|     stEIP150singleCodeGasPrices      | Pending |                    |     |         |          |
|              stEIP1559               | Pending |                    |     |         |          |
|           stEIP158Specific           | 7 |         7           |  0   |         |     100%     |
|              stEIP2930               | Pending |                    |     |         |          |
|              stEIP3607               | Pending |                    |     |         |          |
|              stExample               | Pending |                    |     |         |          |
|            stExtCodeHash             | Pending |                    |     |         |          |
|         stHomesteadSpecific          | 5 |       5             |  0   |         |     100%     |
|            stInitCodeTest            | Pending |                    |     |         |          |
|              stLogTests              | 46 |      46              |  0   |         |   100%       |
|      stMemExpandingEIP150Calls       | Pending |                    |     |         |          |
|          stMemoryStressTest          | Pending |                    |     |         |          |
|             stMemoryTest             | Pending |                    |     |         |          |
|          stNonZeroCallsTest          | Pending |                    |     |         |          |
|        stPreCompiledContracts        | Pending |                    |     |         |          |
|       stPreCompiledContracts2        | Pending |                    |     |         |          |
|      stQuadraticComplexityTest       | Pending |                    |     |         |          |
|               stRandom               | 314 |       166             |  148   |         |    53%      |
|              stRandom2               | Pending |                    |     |         |          |
|          stRecursiveCreate           | Pending |                    |     |         |          |
|             stRefundTest             | Pending |                    |     |         |          |
|           stReturnDataTest           | Pending |                    |     |         |          |
|             stRevertTest             | Pending |                    |     |         |          |
|             stSLoadTest              | 1 |      1              |  0   |         |    100%      |
|             stSStoreTest             | 475 |      135              |   340  |         |   28%       |
|            stSelfBalance             | 8 |        7            |  1   |         |     88%     |
|               stShift                | Pending |                    |     |         |          |
|            stSolidityTest            | Pending |                    |     |         |          |
|            stSpecialTest             | Pending |                    |     |         |          |
|             stStackTests             | Pending |                    |     |         |          |
|             stStaticCall             | Pending |                    |     |         |          |
|         stStaticFlagEnabled          | Pending |                    |     |         |          |
|        stSystemOperationsTest        | Pending |                    |     |         |          |
|           stTimeConsuming            | Pending |                    |     |         |          |
|          stTransactionTest           | Pending |                    |     |         |          |
|           stTransitionTest           | 6 |        6            |  0   |         |    100%      |
|             stWalletTest             | Pending |                    |     |         |          |
|          stZeroCallsRevert           | 16 |       16             |  0   |         |   100%       |
|           stZeroCallsTest            | 24 |       24             |  0   |         |   100%       |
|           stZeroKnowledge            | Pending |                    |     |         |          |
|           stZeroKnowledge2           | Pending |                    |     |         |          |
