# conditional-tokens-tutorial

> Fork of [gnosis/conditional-tokens-tutorial](https://github.com/gnosis/conditional-tokens-tutorial)
>
> **📦 本地备份快照** (2026-07-04) — 原路径 `/opt/workspace/playground/ctf/conditional-tokens-tutorial`

## 这是什么

Gnosis **条件代币预测市场** 的前端教程项目（Create React App）。演示如何创建 LMSR 做市市场、配置 outcome、与链上合约交互。

## 本地改动

| 文件 | 改动 |
|------|------|
| `src/conf/config.local.json` | 本地市场配置（LMSR 地址、市场问题） |
| `src/conf/config.local.json.bak` | 配置备份 |
| `markets.config.js` | 市场列表配置 |
| `.env.example` | 已删除（本地不需要） |

### 配置的市场示例

- 问题：*"Will the summer 2025 in Germany break again weather records?"*
- LMSR 地址：`0x01Da9ec913F82a784ba03eC61CdBCf8877Add8cE`
- 网络：`local`

## 快速开始

```bash
yarn install
yarn start        # 开发服务器
yarn build        # 生产构建
```

需要本地链或测试网环境，配合 `truffle.js` 部署合约。

## 技术栈

- React (CRA) + TypeScript
- Truffle 合约部署
- Web3.js 链上交互

## 上游

https://github.com/gnosis/conditional-tokens-tutorial

## 关联项目

- `qinpeng2/conditional-tokens-market-makers` — AMM 合约 + Python 模拟
- `qinpeng2/ctf-exchange` — CTF 交易所
