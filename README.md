# s1oopX

> 持续学习，深耕交付，写真正跑在公网与日常工具里的代码。  
> *Crafting systems and practical tooling that survive on the public internet.*

---

### ✦ Engineering Philosophy

- **内存真值与最终一致**：库存由 Redis 内存原子保证，一致性交由异步对账与自愈补偿收口。不迷信单一分布式锁，用 CAS 与数据库唯一索引筑牢资损防御底线。
- **资源敬畏与极限防御**：在 1核1G VPS 的物理约束下探索系统上限，以 Linux 内核参数微调、OOM 防御与轻量容器编排守护高可用公网服务。
- **协议优先与底层观测**：相信 Wireshark 与 Burp Suite 抓包里的原始 TCP/TLS 报文，胜过未经生产压测的高层框架抽象。
- **显式契约与工具造物**：以显式协议消除人机上下文孤岛，坚持自主研发日常使用的 CLI、跨端桌面工具与边缘应用，重构个人工作流。

---

### ✦ Selected Works

- **[ReserveX](https://github.com/s1oopX/ReserveX)** · 湿地公园高并发预约系统  
  基于 Redis 7 + Lua 原子扣减、5 桶顺时针环形借桶、RocketMQ 削峰异步落库与四类对账机制。JMeter 27 万样本实测 1,520 QPS (P99 < 26.4ms)。  
  ↳ 在线架构观测台：[reservex.stylex.cyou](https://reservex.stylex.cyou) *(纯黑终端实时 EVALSHA 指令、状态机与沙盒平账)*

- **[agent-memory-workflow](https://github.com/s1oopX/agent-memory-workflow)** · Coding Agent 跨会话长期记忆契约  
  设计 `.agents/` 显式文件契约，物理隔离机器事实与人类审查，打通多端 Agent 对话上下文孤岛，消除全盘冷启动扫描。

- **[Narrow-X](https://github.com/s1oopX/narrow-x)** · 内容优先 Astro 个人站主题  
  安静、克制、高信噪比的个人站与思考载体。追求零运行时 JS 膨胀与接近满分的 Web Vitals 边缘体验。

- **[FolioX](https://github.com/s1oopX/foliox)** · 个人工程化作品集  
  基于 React 19 + Tailwind CSS v4 + Cloudflare 边缘托管，具备严格的 ESLint / Prettier / TypeScript 自动化 CI 质量门禁。  
  ↳ 在线访问：[stylex.cyou](https://stylex.cyou)

---

### ✦ Connect

[Personal Site (s1oopx.bond)](https://s1oopx.bond) · [Portfolio (stylex.cyou)](https://stylex.cyou) · [contact@stylex.cyou](mailto:contact@stylex.cyou)

