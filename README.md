# 素材研究与策划 Agent（Claude Skill）

给定产品 / 品牌 / 主题，自动完成竞品与热点研究，产出**短视频、小红书图文、信息流投放广告**的完整策划案：Brief → 研究洞察 → 创意评分 → 脚本/分镜/文案 → 排期 → 合规自查。

## 独立版素材策划台

[下载独立版 HTML](./素材策划台-独立版.html)，保存后用浏览器打开。页面内填写自己的模型 API Key 即可生成策划案；Key 不包含在仓库文件中。页面样式和脚本已内置，字体需要联网加载。

## 目录结构

```
skills/
└── content-research-planner/
    └── SKILL.md
```

## 安装使用

**Claude.ai / Cowork**
1. 将 `skills/content-research-planner` 文件夹打包为 zip
2. 打开 设置 → Capabilities（功能）→ Skills → 上传 zip

**Claude Code**
```bash
git clone https://github.com/<你的用户名>/content-research-planner.git
mkdir -p ~/.claude/skills
cp -r content-research-planner/skills/content-research-planner ~/.claude/skills/
```

## 使用示例

> 帮我给「XX 品牌冷萃咖啡液」做一份素材策划案，主打小红书和抖音，目标是种草。

## 输出内容

1. 项目 Brief
2. 研究洞察表（附来源）
3. 创意方向与评分
4. 短视频脚本 + 分镜表
5. 小红书图文方案
6. 投放广告多版本文案 + A/B 测试
7. 执行排期与制作清单
8. 数据复盘指标
