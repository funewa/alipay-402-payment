# alipay-402-payment

> WorkBuddy Skill — `alipay-402-payment`

## 简介

在 WorkBuddy / CodeBuddy 客户端内完成支付宝 HTTP 402 按量付费（Payment-Needed 头）。 适用于调用返回 402 且带 Payment-Needed / amtPaymentLink 响应头的付费 Skill 或 API， 例如 amazon-voc-pay 这类「按次付费、无需注册」的技能。 Use when a tool, skill or API returns HTTP 402 with a Payment-Needed header and 

## 安装

```bash
git clone https://github.com/funewa/alipay-402-payment.git
cp -r alipay-402-payment ~/.workbuddy/skills/alipay-402-payment
```

## 使用

在 WorkBuddy 中直接描述你的需求，Agent 会依据 `SKILL.md` 的 `description` 自动匹配本技能。详见 `SKILL.md`。

## 目录结构

```
├── SKILL.md      # 技能定义（frontmatter + 说明）
└── README.md
```

---

Published from the `user`-level WorkBuddy skill library.
