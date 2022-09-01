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

## Overview
| Total | Generation errors | Ignored | :heavy_check_mark: | :x:  | Coverage |
|:-----:|:-----------------:|:-------:|:------------------:|:----:|:--------:|
| 13282 |       1695        |   1746  |        8336        | 1505 |   72%    |

## Extended table

|             Folder Name              | Total | :heavy_check_mark: | :x: | Ignored | Cov  |
|:------------------------------------:|:-----:|:------------------:|:---:|:-------:|:----:|
|         stArgsZeroOneBalance         |  96   |         96         |  0  |    0    | 100% |
|             stAttackTest             |   2   |         1          |  1  |    0    | 50%  |
|             stBadOpcode              |  203  |        175         | 28  |    0    | 86%  |
|                stBugs                |   9   |         9          |  0  |    0    | 100% |
|             stCallCodes              |  87   |         63         | 24  |    0    | 72%  |
|       stCallCreateCallCodeTest       |  55   |         35         | 20  |    0    | 64%  |
| stCallDelegateCodesCallCodeHomestead |  58   |         37         | 21  |    0    | 64%  |
|     stCallDelegateCodesHomestead     |  58   |         37         | 21  |    0    | 64%  |
|              stChainId               |   2   |         1          |  0  |    1    | 100% |
|            stCodeCopyTest            |   2   |         2          |  0  |    0    | 100% |
|           stCodeSizeLimit            |   5   |         3          |  2  |    0    | 60%  |
|              stCreate2               |  154  |        117         | 21  |   16    | 85%  |
|             stCreateTest             |  95   |         79         | 16  |    0    | 83%  |
|     stDelegatecallTestHomestead      |  31   |         20         | 11  |    0    | 65%  |
|           stEIP150Specific           |  13   |         13         |  0  |    0    | 100% |
|     stEIP150singleCodeGasPrices      |  339  |        335         |  4  |    0    | 99%  |
|              stEIP1559               |   1   |         1          |  0  |    0    | 100% |
|           stEIP158Specific           |   7   |         7          |  0  |    0    | 100% |
|              stEIP2930               |  138  |         6          | 132 |    0    |  4%  |
|              stEIP3607               |   5   |         0          |  5  |    0    |  0%  |
|              stExample               |  38   |         35         |  3  |    0    | 92%  |
|            stExtCodeHash             |  65   |         18         | 47  |    0    | 28%  |
|         stHomesteadSpecific          |   5   |         5          |  0  |    0    | 100% |
|            stInitCodeTest            |  22   |         14         |  8  |    0    | 64%  |
|              stLogTests              |  46   |         46         |  0  |    0    | 100% |
|      stMemExpandingEIP150Calls       |  10   |         8          |  2  |    0    | 80%  |
|          stMemoryStressTest          |  82   |         40         | 42  |    0    | 49%  |
|             stMemoryTest             |  578  |        202         | 126 |   250   | 62%  |
|          stNonZeroCallsTest          |  24   |         24         |  0  |    0    | 100% |
|        stPreCompiledContracts        |  960  |        111         | 823 |   26    | 12%  |
|       stPreCompiledContracts2        |  203  |         51         | 26  |   126   | 66%  |
|      stQuadraticComplexityTest       |  32   |         7          | 25  |    0    | 22%  |
|               stRandom               |  313  |        176         | 137 |    0    | 56%  |
|              stRandom2               |  226  |        121         | 105 |    0    | 54%  |
|          stRecursiveCreate           |   2   |         0          |  2  |    0    |  0%  |
|             stRefundTest             |  26   |         21         |  5  |    0    | 81%  |
|           stReturnDataTest           |  81   |         42         | 39  |    0    | 52%  |
|             stRevertTest             |  271  |        172         | 99  |    0    | 63%  |
|             stSLoadTest              |   1   |         1          |  0  |    0    | 100% |
|             stSStoreTest             |  475  |        467         |  0  |    8    | 100% |
|            stSelfBalance             |   7   |         7          |  0  |    0    | 100% |
|               stShift                |  42   |         32         | 10  |    0    | 76%  |
|            stSolidityTest            |  23   |         14         |  9  |    0    | 61%  |
|            stSpecialTest             |  14   |         7          |  7  |    0    | 50%  |
|             stStackTests             |  375  |        312         | 63  |    0    | 83%  |
|             stStaticCall             |  478  |        303         | 175 |    0    | 63%  |
|         stStaticFlagEnabled          |  34   |         24         | 10  |    0    | 71%  |
|        stSystemOperationsTest        |  69   |         53         | 16  |    0    | 77%  |
|           stTimeConsuming            | 5190  |        4227        | 963 |    0    | 81%  |
|          stTransactionTest           |  168  |        165         |  3  |    0    | 98%  |
|           stTransitionTest           |   6   |         6          |  0  |    0    | 100% |
|             stWalletTest             |  46   |         46         |  0  |    0    | 100% |
|          stZeroCallsRevert           |  16   |         16         |  0  |    0    | 100% |
|           stZeroCallsTest            |  24   |         24         |  0  |    0    | 100% |
|           stZeroKnowledge2           |  519  |         0          |  0  |   519   | 100% |
|           stZeroKnowledge            |  800  |         0          |  0  |   800   | 100% |
|               VMTests                |  651  |        502         | 149 |    0    | 77%  |
