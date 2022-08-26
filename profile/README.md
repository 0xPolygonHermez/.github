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
| 12704 |       2026        |   1496   |        7672        | 1510 |   68%    |

## Extended table

|             Folder Name              | STARTED | DONE | ONGOING | Total | :heavy_check_mark: | :x: | Ignored | Cov  |
|:------------------------------------:| ------- | ---- |:-------:|:-----:|:------------------:|:---:|:-------:|:----:|
|         stArgsZeroOneBalance         |         | x    |         |  96   |         93         |  3  |    0    | 97%  |
|             stAttackTest             |         |      |         |   2   |         1          |  1  |    0    | 50%  |
|             stBadOpcode              | x       |      |         |  203  |        174         | 29  |    0    | 86%  |
|                stBugs                |         |      |         |   9   |         4          |  5  |    0    | 44%  |
|             stCallCodes              | x       |      |         |  87   |         62         | 25  |    0    | 71%  |
|       stCallCreateCallCodeTest       |         |      |         |  55   |         33         | 22  |    0    | 60%  |
| stCallDelegateCodesCallCodeHomestead | x       |      |         |  58   |         37         | 21  |    0    | 64%  |
|     stCallDelegateCodesHomestead     | x       |      |         |  58   |         37         | 21  |    0    | 64%  |
|              stChainId               | x       | x    |         |   2   |         1          |  0  |    1    | 100% |
|            stCodeCopyTest            | x       | x    |         |   2   |         2          |  0  |    0    | 100% |
|           stCodeSizeLimit            |         |      |         |   5   |         3          |  2  |    0    | 60%  |
|              stCreate2               |         |      |         |  154  |        102         | 36  |   16    | 74%  |
|             stCreateTest             | x       |      |    x    |  95   |         66         | 29  |    0    | 69%  |
|     stDelegatecallTestHomestead      |         |      |         |  31   |         20         | 11  |    0    | 65%  |
|           stEIP150Specific           |         |      |         |  13   |         12         |  1  |    0    | 92%  |
|     stEIP150singleCodeGasPrices      |         |      |         |  339  |        335         |  4  |    0    | 99%  |
|              stEIP1559               |         |      |         |   1   |         0          |  1  |    0    |  0%  |
|           stEIP158Specific           | x       | x    |         |   7   |         7          |  0  |    0    | 100% |
|              stEIP2930               |         |      |         |  138  |         6          | 132 |    0    |  4%  |
|              stEIP3607               |         |      |         |   5   |         0          |  5  |    0    |  0%  |
|              stExample               |         |      |         |  38   |         32         |  6  |    0    | 84%  |
|            stExtCodeHash             | x       |      |         |  65   |         18         | 47  |    0    | 28%  |
|         stHomesteadSpecific          |         |      |         |   5   |         5          |  0  |    0    | 100% |
|            stInitCodeTest            |         |      |         |  22   |         14         |  8  |    0    | 64%  |
|              stLogTests              | x       | x    |         |  46   |         46         |  0  |    0    | 100% |
|      stMemExpandingEIP150Calls       |         |      |         |  10   |         7          |  3  |    0    | 70%  |
|          stMemoryStressTest          |         |      |         |  82   |         10         | 72  |    0    | 12%  |
|             stMemoryTest             | x       |      |    x    |  578  |        211         | 367 |         |  37  |
|          stNonZeroCallsTest          |         |      |         |  24   |         24         |  0  |    0    | 100% |
|        stPreCompiledContracts        | x       |      |    x    |  960  |        109         | 825 |   26    | 12%  |
|       stPreCompiledContracts2        |         |      |         |  203  |         50         | 27  |   126   | 65%  |
|      stQuadraticComplexityTest       |         |      |         |  32   |         0          | 32  |    0    |  0%  |
|               stRandom               |         |      |         |  313  |        173         | 140 |    0    | 55%  |
|              stRandom2               |         |      |         |  226  |        116         | 110 |    0    | 51%  |
|          stRecursiveCreate           |         |      |         |   2   |         0          |  2  |    0    |  0%  |
|             stRefundTest             |         |      |         |  26   |         18         |  8  |    0    | 69%  |
|           stReturnDataTest           |         |      |         |  81   |         42         | 39  |    0    | 52%  |
|             stRevertTest             |         |      |         |  271  |         95         | 176 |    0    | 35%  |
|             stSLoadTest              | x       | x    |         |   1   |         1          |  0  |    0    | 100% |
|             stSStoreTest             | x       |      |         |  475  |        243         | 224 |    8    | 52%  |
|            stSelfBalance             |         | x    |    x    |   7   |         7          |  0  |    0    | 100% |
|               stShift                |         |      |         |  42   |         32         | 10  |    0    | 76%  |
|            stSolidityTest            |         |      |         |  23   |         14         |  9  |    0    | 61%  |
|            stSpecialTest             |         |      |         |  14   |         7          |  7  |    0    | 50%  |
|             stStackTests             |         |      |         |  375  |        312         | 63  |    0    | 83%  |
|             stStaticCall             |         |      |         |  478  |        271         | 207 |    0    | 57%  |
|         stStaticFlagEnabled          |         |      |         |  34   |         24         | 10  |    0    | 71%  |
|        stSystemOperationsTest        |         |      |         |  69   |         44         | 25  |    0    | 64%  |
|           stTimeConsuming            |         |      |         | 5190  |        4227        | 963 |    0    | 81%  |
|          stTransactionTest           |         |      |         |  168  |        158         | 10  |    0    | 94%  |
|           stTransitionTest           |         | x    |         |   6   |         6          |  0  |    0    | 100% |
|             stWalletTest             |         | x    |         |  46   |         46         |  0  |    0    | 100% |
|          stZeroCallsRevert           |         | x    |         |  16   |         0          | 16  |    0    |  0%  |
|           stZeroCallsTest            |         | x    |         |  24   |         24         |  0  |    0    | 100% |
|           stZeroKnowledge2           |         |      |         |  519  |         0          |  0  |   519   | 100% |
|           stZeroKnowledge            |         |      |         |  800  |         0          |  0  |   800   | 100% |
|               VMTests                |         |      |         |  651  |        502         | 149 |    0    | 77%  |
