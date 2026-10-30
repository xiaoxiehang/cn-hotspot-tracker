# cn-hotspot-tracker

中文互联网热点追踪 Skill：8 平台检索 → 交叉验证 → 分级报告，给 Agent 用的热点方法论。

## 用法

```bash
npx skills add https://github.com/xiaoxiehang/cn-hotspot-tracker
```

或把 `SKILL.md` 放到 skills 目录，对 Agent 说"今日热点扫描"即可。

## 设计要点

- **防单平台幻觉**：≥2 平台同时上榜 + 可验证原始来源才算真热点
- **分级输出**：S（全网级）/ A（垂类级）/ B（观察级），只对 S/A 做跟进决策
- **与内容生产衔接**：热点只解决"写什么"；教程垂类只追"热点×垂类"交叉点，12 小时决断，过期不追

## License

MIT
