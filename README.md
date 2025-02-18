# 全球财报日历订阅服务 📅

自动同步美股/中国上市公司财报发布日程的iCal订阅服务，支持主流日历应用实时更新

![img_v3_02jl_b6ab1ff9-5df9-449b-ae48-2bd267ca73ag](https://github.com/user-attachments/assets/c32a65dc-ae8f-4af8-bbac-58c73f9a8156)
![img_v3_02jl_4c65ea39-b50e-4090-aa19-b2bee3d6597g](https://github.com/user-attachments/assets/8dcf60d9-3cda-4ff3-9885-08b1565db15a)
![img_v3_02jl_b672be5f-3a64-45c5-94ad-35c9e8fef3fg](https://github.com/user-attachments/assets/24cb9729-771c-405a-86f1-77dc001cb250)


## ✨ 核心功能
- **双向市场覆盖**
  - 美股：NYSE/NASDAQ上市公司
  - 中国股：沪深交易所上市公司
- **智能更新机制**
  - 自动抓取最新财报计划
  - 季度/年度报告自动区分
  - T+1数据同步保证
- **全平台兼容**
  - 支持Google Calendar/Outlook/iOS日历等
  - 标准iCal协议(ICS格式)

## 🚀 快速接入
1. 复制订阅地址：
   ```text
   https://raw.githubusercontent.com/penouc/finance-calendar/refs/heads/main/earnings_calendar.ics
   ```
2. 打开您的日历应用：
   - **Google Calendar**：侧边栏 > 其他日历 > 从URL添加
   - **Outlook**：日历视图 > 添加日历 > 从网络订阅
   - **iOS**：设置 > 日历 > 账户 > 添加账户 > 其他 > 添加订阅日历


## 🔄 更新机制
- 数据源：聚合权威财经平台数据
- 更新频率：每日UTC 00:00自动同步
- 异常处理：自动重试机制保障数据连续性

## 🤝 参与贡献
欢迎通过以下方式改进项目：
1. 提交Issue报告数据异常
2. 发起PR改进抓取算法
3. 扩展其他证券市场支持

## 📄 授权协议
本项目基于 [MIT License](LICENSE) 开源
