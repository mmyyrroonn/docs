# Total

Human resource: 1 contract dev + 1 backend dev + 1~2 frontend dev + 1 UI + 1 QA/OPs + 1 product manager

Time: 4 months

Note:
- UI和产品设计要前置 (合约开发依赖产品设计，前端开发依赖UI)
- 合约开发要略微前置 (后续 Service 和前端开发依赖合约接口)，后端 Service 和前端开发可以并行
- 3 ~ 4 个月为项目第一个版本的总体开发时间

# Break Down
## 合约
### Settlements 合约
#### Total
- 1 contract dev, 5 weeks

#### Break Down
- Settlement & VRF: 2 week
- Cancel & Probability: 1 week
- Combination with Marketplace SC: 1 week
- Test Case: 1 week
- 代码审计: ?

### Marketplace 合约
#### Total
- 1 contract dev, 6~8 weeks

#### Break Down
- Policy Manager: 1 week
- Main Exchange: 2 week
- (Optional) ETH Pool Deposit & Withdraw: 2 week
- Matching Policy: 1 week
- Execution Delegate: 1 week
- Test Case: 1 week
- 代码审计: ?


## 后端
### Total
- 1 backend dev, 8 ~ 10 weeks

#### Break Down
- DB Schema & DAO: 1 week
- 链上数据索引聚合: 2 ~ 3 weeks
- NFT数据索引聚合: 2 ~ 3 weeks (Reservoir SDK)
- API (前端 Portal，或者): 1 ~ 2 weeks


## 前端
### Total
- 1 frontend dev, ~ 9 weeks
- 1 UI, 4 weeks

## Break Down
- Marketplace 合约交互 SDK 封装 (如果不使用或者适配 Reservoir SDK/API): 2 weeks
    - 封装的 SDK 前后端可以共用
- Welcome Page
    - UI 设计: 1 week
    - 开发:  2 week
- NFT Profile Page
    - UI 设计: 1 week
    - 开发: 1.5 week
- Collections Page
    - UI 设计: 2 days
    - 开发: 0.5 week
- Portfolio Page
    - UI 设计: 3 days
    - 开发: 1 week
- Activity Page
    - UI 设计: 3 days
    - 开发: 1 week
- Listing(Sell) Page
    - UI 设计: 2 day
    - 开发: 0.5 week
- Buy Page
    - UI 设计: 1 day
    - 开发: 0.5 week

## 联调
前端 + 后端 + 合约: 3 weeks
