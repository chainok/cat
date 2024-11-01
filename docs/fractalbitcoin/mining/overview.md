# 概述

## 减半周期
减半周期为 2,100,000 个区块。

创世区块向中本聪的地址生成了 50 BTC，但这笔金额是不可花费的。在创世区块之后的第一个区块中，将预先分配总计 1.05 亿的挖矿产出到一个可支配地址。

从第二个区块开始，每个区块将生成 25 FB，保持 8 位小数精度。

总挖矿供应量计算为：2 * 25 * 2,100,000 = 1.05 亿 FB。

## 共识机制
Fractal 采用与比特币一致的工作量证明（Proof-of-Work）机制。矿工可以使用现有的 ASIC 矿机和其他硬件设备进行挖矿（标准 SHA256d）。

## 节奏挖矿（Cadence Mining）
Fractal 使用创新的"节奏挖矿"方法来平衡合并挖矿和无许可挖矿的优势，在安全性和包容性之间取得平衡。这种混合模型使矿工能够增强网络安全性，同时参与 Fractal 提供的经济收益。

出块间隔为 30 秒。每三个区块中，两个区块将通过无许可挖矿产生，一个区块通过合并挖矿产生。

这种机制既保留了 Fractal 社区自由可用的无许可挖矿机会，同时通过合并挖矿利用比特币主链的强大安全性。

Fractal Bitcoin 支持与比特币进行合并挖矿，允许矿工在挖掘比特币主网的同时挖掘 Fractal Bitcoin 区块。集成机制与域名币（Namecoin）相同。

## 初始难度和算力要求

### 无许可挖矿：
- nbits: 0x1900cfff
- 难度：约 5G
- 算力要求：约 500 PH/s

### 合并挖矿：
- nbits: 0x180cffff
- 难度：约 400G
- 算力要求：约 20 EH/s（相当于比特币算力的 3.2%）