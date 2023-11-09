
![Polygon zkEVM logo dark](https://user-images.githubusercontent.com/18598517/235932702-bc47eae5-d672-4dd9-9da2-8ea8f51a93f3.png)
</div>
<br />
<div align="center">

[![Chat on Twitter][ico-twitter]][link-twitter]
[![Website][ico-website]][link-website]

</div>

[ico-twitter]: https://img.shields.io/twitter/url?label=polygonZkEVM&style=social&url=https%3A%2F%2Ftwitter.com%2F0xPolygon
[ico-website]: https://img.shields.io/static/v1?label=docs&message=polygonZkEVM&color=7B3FE4

[link-twitter]: https://twitter.com/0xPolygon
[link-website]: https://wiki.polygon.technology/docs/zkEVM/introduction


- `polygon zkEVM` is a new zk-rollup that provides Ethereum Virtual Machine (EVM) equivalence (opcode-level compatibility) for a transparent user experience and existing Ethereum ecosystem and tooling compatibility.
- It consists on a decentralized Ethereum Layer 2 scalability solution utilising cryptographic zero-knowledge technology to provide validation and fast finality of off-chain transaction computations.
- This approach required the recreation of all EVM opcodes for transparent deployment and transactions with existing Ethereum smart contracts. For this purpose a new set of tools and technologies were created and engineered and are contained in this organization.

## Testnet/Mainnet versions
The following table shows the recommended versions to use for permissionless nodes:
| Network | Node | Prover/Executor |
|:--------|:-----|:----------------|
|mainnet  |[v0.3.3](https://github.com/0xPolygonHermez/zkevm-node/releases/tag/v0.3.3)|[v3.0.0](https://github.com/0xPolygonHermez/zkevm-prover/releases/tag/v3.0.0)|
|testnet  |[v0.3.2](https://github.com/0xPolygonHermez/zkevm-node/releases/tag/v0.3.2)|[v3.0.0](https://github.com/0xPolygonHermez/zkevm-prover/releases/tag/v3.0.0)|

## Ethereum compatibility
- The following table aims to summarize the zkEVM compatibility with the [official Ethereum test vectors](https://github.com/ethereum/tests)
- The test vectors targeted are located [here](https://github.com/ethereum/tests/tree/develop/BlockchainTests/GeneralStateTests)
- Detailed information could be found in the [zkevm-testvectors repository](https://github.com/0xPolygonHermez/zkevm-testvectors)

## Overview
- Commit [ethereum/tests](https://github.com/ethereum/tests): 24fa31adb30f71ee700b27decb5204e53a11d9f3
- Commit [zkevm-testvectors](https://github.com/0xPolygonHermez/zkevm-testvectors): 51fce991e0621c4397e122fc6d24794bc10f0fc5
- Commit [zkevm-rom](https://github.com/0xPolygonHermez/zkevm-rom): a428ddc391044032ef285105e52624bc2051dbcb
- Commit [zkevm-proverjs](https://github.com/0xPolygonHermez/zkevm-proverjs): cedc278e4fbc93b84e8ea4008d9fa4ab590ce08f

| Total | Generation errors | Ignored | :heavy_check_mark: | :x: | Coverage |
|:-----:|:-----------------:|:-------:|:------------------:|:---:|:--------:|
| 17799 |         48        |  3034   |        14717       |  0  |  99.67%  |

## Extended table

|             Folder Name              | Total | :heavy_check_mark: | :x: | Ignored |  Cov   |
|:------------------------------------:|:-----:|:------------------:|:---:|:-------:|:------:|
|         stArgsZeroOneBalance         |  96   |         94         |  0  |    2    | 100.00 |
|             stAttackTest             |   2   |         0          |  0  |    2    | 100.00 |
|             stBadOpcode              | 4250  |        4104        |  1  |   145   | 99.98  |
|                stBugs                |   9   |         7          |  0  |    2    | 100.00 |
|             stCallCodes              |  87   |         67         |  0  |   20    | 100.00 |
|       stCallCreateCallCodeTest       |  55   |         39         |  0  |   16    | 100.00 |
| stCallDelegateCodesCallCodeHomestead |  58   |         41         |  0  |   17    | 100.00 |
|     stCallDelegateCodesHomestead     |  58   |         41         |  0  |   17    | 100.00 |
|              stChainId               |   2   |         1          |  0  |    1    | 100.00 |
|            stCodeCopyTest            |   2   |         2          |  0  |    0    | 100.00 |
|           stCodeSizeLimit            |   6   |         6          |  0  |    0    | 100.00 |
|              stCreate2               |  174  |        129         |  1  |   44    | 99.23  |
|             stCreateTest             |  173  |        135         |  3  |   35    | 97.83  |
|     stDelegatecallTestHomestead      |  31   |         26         |  0  |    5    | 100.00 |
|           stEIP150Specific           |  25   |         23         |  0  |    2    | 100.00 |
|     stEIP150singleCodeGasPrices      |  339  |        329         |  0  |   10    | 100.00 |
|              stEIP1559               |  44   |         0          |  0  |   44    | 100.00 |
|           stEIP158Specific           |   7   |         4          |  0  |    3    | 100.00 |
|              stEIP2930               |  138  |         3          |  0  |   135   | 100.00 |
|              stEIP3607               |  12   |         12         |  0  |    0    | 100.00 |
|              stExample               |  38   |         34         |  0  |    4    | 100.00 |
|            stExtCodeHash             |  65   |         16         |  0  |   49    | 100.00 |
|         stHomesteadSpecific          |   5   |         5          |  0  |    0    | 100.00 |
|            stInitCodeTest            |  22   |         20         |  0  |    2    | 100.00 |
|              stLogTests              |  46   |         46         |  0  |    0    | 100.00 |
|      stMemExpandingEIP150Calls       |  10   |         10         |  0  |    0    | 100.00 |
|          stMemoryStressTest          |  82   |         79         |  0  |    3    | 100.00 |
|             stMemoryTest             |  578  |        567         |  0  |   11    | 100.00 |
|          stNonZeroCallsTest          |  24   |         20         |  0  |    4    | 100.00 |
|        stPreCompiledContracts        |  960  |        425         |  0  |   535   | 100.00 |
|       stPreCompiledContracts2        |  248  |        100         |  0  |   148   | 100.00 |
|      stQuadraticComplexityTest       |  32   |         17         |  6  |    9    | 73.91  |
|               stRandom               |  313  |        262         |  4  |   47    | 98.50  |
|              stRandom2               |  226  |        205         |  0  |   21    | 100.00 |
|          stRecursiveCreate           |   2   |         2          |  0  |    0    | 100.00 |
|             stRefundTest             |  26   |         11         |  0  |   15    | 100.00 |
|           stReturnDataTest           |  273  |        237         |  0  |   36    | 100.00 |
|             stRevertTest             |  271  |        168         |  0  |   103   | 100.00 |
|             stSLoadTest              |   1   |         1          |  0  |    0    | 100.00 |
|             stSStoreTest             |  475  |        467         |  0  |    8    | 100.00 |
|            stSelfBalance             |  42   |         40         |  0  |    2    | 100.00 |
|               stShift                |  42   |         42         |  0  |    0    | 100.00 |
|            stSolidityTest            |  23   |         18         |  0  |    5    | 100.00 |
|            stSpecialTest             |  22   |         10         |  2  |   10    | 83.33  |
|             stStackTests             |  375  |        375         |  0  |    0    | 100.00 |
|             stStaticCall             |  478  |        393         | 10  |   75    | 97.52  |
|         stStaticFlagEnabled          |  34   |         25         |  0  |    9    | 100.00 |
|        stSystemOperationsTest        |  72   |         54         |  0  |   18    | 100.00 |
|           stTimeConsuming            | 5190  |        5187        |  0  |    3    | 100.00 |
|          stTransactionTest           |  164  |        148         |  0  |   16    | 100.00 |
|           stTransitionTest           |   6   |         6          |  0  |    0    | 100.00 |
|             stWalletTest             |  46   |         43         |  0  |    3    | 100.00 |
|          stZeroCallsRevert           |  16   |         12         |  0  |    4    | 100.00 |
|           stZeroCallsTest            |  24   |         20         |  0  |    4    | 100.00 |
|           stZeroKnowledge2           |  519  |         0          |  0  |   519   | 100.00 |
|           stZeroKnowledge            |  800  |         0          |  0  |   800   | 100.00 |
|               VMTests                |  651  |        578         | 14  |   59    | 97.64  |
