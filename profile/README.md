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
- Commit [zkevm-testvectors](https://github.com/0xPolygonHermez/zkevm-testvectors): 919bbf9ea406b55fea94faf4e0a7d96aa20cde57
- Commit [zkevm-rom](https://github.com/0xPolygonHermez/zkevm-rom): 09b2ec3be4a699d3abcc8e5fd99ca50a59c8da17
- Commit [zkevm-proverjs](https://github.com/0xPolygonHermez/zkevm-proverjs): b8e49f0be4239bc1df7eb9a83d7b0c4443e2a1ae

| Total | Generation errors | Ignored | :heavy_check_mark: | :x:  | Coverage |
|:-----:|:-----------------:|:-------:|:------------------:|:----:|:--------:|
| 13282 |        251        |   3065  |        8658        | 1308 |   85%    |

## Table

|             Folder Name              | Total | :heavy_check_mark: | :x: | Ignored | Cov  |
|:------------------------------------:|:-----:|:------------------:|:---:|:-------:|:----:|
|         stArgsZeroOneBalance         |  96   |         94         |  0  |    2    | 100% |
|             stAttackTest             |   2   |         0          |  0  |    2    | 100% |
|             stBadOpcode              |  203  |        172         |  6  |   25    | 97%  |
|                stBugs                |   9   |         7          |  0  |    2    | 100% |
|             stCallCodes              |  87   |         60         |  7  |   20    | 90%  |
|       stCallCreateCallCodeTest       |  55   |         32         | 12  |   11    | 73%  |
| stCallDelegateCodesCallCodeHomestead |  58   |         34         |  7  |   17    | 83%  |
|     stCallDelegateCodesHomestead     |  58   |         35         |  6  |   17    | 85%  |
|              stChainId               |   2   |         1          |  0  |    1    | 100% |
|            stCodeCopyTest            |   2   |         2          |  0  |    0    | 100% |
|           stCodeSizeLimit            |   5   |         5          |  0  |    0    | 100% |
|              stCreate2               |  154  |        107         |  3  |   44    | 97%  |
|             stCreateTest             |  95   |         73         |  9  |   13    | 89%  |
|     stDelegatecallTestHomestead      |  31   |         23         |  8  |    0    | 74%  |
|           stEIP150Specific           |  13   |         11         |  0  |    2    | 100% |
|     stEIP150singleCodeGasPrices      |  339  |        326         |  3  |   10    | 99%  |
|              stEIP1559               |   1   |         0          |  1  |    0    |  0%  |
|           stEIP158Specific           |   7   |         4          |  0  |    3    | 100% |
|              stEIP2930               |  138  |         29         | 77  |   32    | 27%  |
|              stEIP3607               |   5   |         0          |  5  |    0    |  0%  |
|              stExample               |  38   |         32         |  6  |    0    | 84%  |
|            stExtCodeHash             |  65   |         14         | 32  |   19    | 30%  |
|         stHomesteadSpecific          |   5   |         4          |  1  |    0    | 80%  |
|            stInitCodeTest            |  22   |         21         |  0  |    1    | 100% |
|              stLogTests              |  46   |         46         |  0  |    0    | 100% |
|      stMemExpandingEIP150Calls       |  10   |         8          |  2  |    0    | 80%  |
|          stMemoryStressTest          |  82   |         44         |  6  |   32    | 88%  |
|             stMemoryTest             |  578  |        221         |  2  |   355   | 99%  |
|          stNonZeroCallsTest          |  24   |         12         |  8  |    4    | 60%  |
|        stPreCompiledContracts        |  960  |        548         | 181 |   231   | 75%  |
|       stPreCompiledContracts2        |  203  |         53         |  9  |   141   | 85%  |
|      stQuadraticComplexityTest       |  32   |         10         | 11  |   11    | 48%  |
|               stRandom               |  313  |        149         | 34  |   130   | 81%  |
|              stRandom2               |  226  |        149         | 31  |   46    | 83%  |
|          stRecursiveCreate           |   2   |         2          |  0  |    0    | 100% |
|             stRefundTest             |  26   |         13         |  0  |   13    | 100% |
|           stReturnDataTest           |  81   |         40         | 10  |   31    | 80%  |
|             stRevertTest             |  271  |        135         |  4  |   132   | 97%  |
|             stSLoadTest              |   1   |         1          |  0  |    0    | 100% |
|             stSStoreTest             |  475  |        467         |  0  |    8    | 100% |
|            stSelfBalance             |   7   |         7          |  0  |    0    | 100% |
|               stShift                |  42   |         32         |  9  |    1    | 78%  |
|            stSolidityTest            |  23   |         17         |  1  |    5    | 94%  |
|            stSpecialTest             |  14   |         6          |  4  |    4    | 60%  |
|             stStackTests             |  375  |        192         | 10  |   173   | 95%  |
|             stStaticCall             |  478  |        368         | 38  |   72    | 91%  |
|         stStaticFlagEnabled          |  34   |         24         |  0  |   10    | 100% |
|        stSystemOperationsTest        |  69   |         48         |  7  |   14    | 87%  |
|           stTimeConsuming            | 5190  |        4227        | 960 |    3    | 81%  |
|          stTransactionTest           |  168  |        148         | 11  |    9    | 93%  |
|           stTransitionTest           |   6   |         6          |  0  |    0    | 100% |
|             stWalletTest             |  46   |         43         |  0  |    3    | 100% |
|          stZeroCallsRevert           |  16   |         12         |  0  |    4    | 100% |
|           stZeroCallsTest            |  24   |         12         |  8  |    4    | 60%  |
|           stZeroKnowledge2           |  519  |         0          |  0  |   519   | 100% |
|           stZeroKnowledge            |  800  |         0          |  0  |   800   | 100% |
|               VMTests                |  651  |        532         | 30  |   89    | 95%  |