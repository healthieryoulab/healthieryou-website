---
layout: default
title: Privacy Policy
permalink: /privacy.html
---

# Privacy Policy · Healthier You Calorie

**Last updated**: May 10, 2026

---

> Bilingual (English first, 简体中文 below). Both versions are part of the policy. In case of conflict, the English version controls.

---

## English

### 1. Who we are

Healthier You Calorie is a mobile application that helps you keep a photo-based meal journal with AI-assisted calorie estimates. This privacy policy explains what data we collect, how we use it, and the choices you have.

This policy applies to the Healthier You Calorie iOS app and its supporting services (the "Service"). It does not apply to third-party websites or services linked from the Service.

If you have questions about this policy, contact us at **healthieryou.support@gmail.com**.

### 2. Data we collect

We collect only the data needed to operate the Service:

**Account information**
- Email address (when you sign up with email and password) or Apple Sign In identifier
- Optional name from Apple Sign In, if you choose to share it

**Profile information**
- Age, biological sex, height, and weight
- Computed BMI and BMR (basal metabolic rate)

**Meal records**
- Meal photos you upload for AI analysis
- AI-generated text and structured data (food names, estimated weights, calorie ranges)
- Edits or notes you make to a meal
- The date and time you log a meal

**Daily activity**
- Self-reported daily exercise calories

**Subscription state**
- Whether you have an active subscription, the current product, the renewal date, and the original Apple transaction identifier
- We do not access your credit card or bank information; payment is processed by Apple

**Feedback**
- Free-text feedback you submit through the Feedback form, plus the type tag (issue or suggestion)

**Operational logs**
- Standard server logs (timestamps, request paths, error messages) needed to operate and debug the Service

We do not collect location, contacts, browsing history, advertising identifiers (IDFA), or device sensor data.

### 3. How we use your data

We use the data above only to:
- Provide the core Service: AI calorie estimation, meal journal display, statistics, and account management
- Manage subscription state and entitlements
- Process and respond to feedback you submit
- Operate and debug the Service (server logs)
- Comply with legal obligations

We do **not**:
- Sell or rent your data
- Use your data to train third-party AI models
- Use your data for advertising or cross-app tracking

### 4. Photos and AI processing

When you submit a meal photo for analysis:
- The photo is uploaded to our servers and forwarded to OpenAI's API for analysis
- OpenAI returns recognized food items and estimated calorie ranges
- We generate a small thumbnail (256×256) for display in your meal journal
- The original full-resolution photo is removed from active storage shortly after processing
- We do not send your account identifier or personal information to OpenAI; only the photo bytes and request metadata required by their API

OpenAI does not retain content submitted via its API for training, per its Enterprise Privacy commitments. See [OpenAI Enterprise Privacy](https://openai.com/enterprise-privacy/) for the operative third-party terms.

If a photo cannot be processed (network error, AI failure, or content rejection), no meal record is created and no free uses are deducted from your account.

### 5. Third-party services

We rely on the following processors:

| Provider | Purpose | Data shared |
| --- | --- | --- |
| Apple (App Store, StoreKit) | Account sign-in (Sign in with Apple), in-app purchase processing | Sign In tokens, transaction identifiers |
| Supabase | Account auth, database, file storage | All account, meal, and subscription data above |
| OpenAI | AI photo analysis | Meal photo bytes only (no account identifier) |

Each provider processes data on our behalf under its own privacy and security commitments.

### 6. Data retention

- **Active account data** (profile, meals, thumbnails, subscription state, feedback) is kept while your account is active.
- **Soft-deleted meals** are removed from your view immediately and physically purged within thirty days.
- **Original meal photos** are removed from active storage shortly after AI processing.
- **Account deletion** removes profile, meals, thumbnails, daily exercise records, feedback submissions, and subscription state. Server-side cleanup runs in the background and completes within a reasonable period.
- **Operational logs** may be retained for up to 90 days for debugging, then automatically rotated.

### 7. Your choices

- **View your data**: All data we collect about your account is visible inside the app.
- **Edit a meal**: You can edit the total calorie estimate for any saved meal.
- **Delete a meal**: Tap any meal in your journal and choose Delete.
- **Delete your account**: Settings → Account → Delete account. This permanently removes your data. We cannot recover deleted accounts.
- **Manage your subscription**: Settings → Subscription → Manage subscription opens your Apple ID subscription settings.

### 8. Children's privacy

Healthier You Calorie is not directed to children under 13. We do not knowingly collect data from children under 13. If you believe a child has created an account, contact us at **healthieryou.support@gmail.com** and we will remove the account.

### 9. Changes to this policy

We may update this policy from time to time. Material changes will be reflected in the "Last updated" date above and, where appropriate, surfaced in the app.

### 10. Contact

For questions, requests, or concerns about your data:
**healthieryou.support@gmail.com**

---

## 简体中文

### 1. 我们是谁

Healthier You · 饮食日记 是一款帮助你以照片方式记录饮食、并由 AI 协助估算热量的移动应用程序。本隐私政策说明我们收集哪些数据、如何使用，以及你拥有的选择。

本政策适用于 Healthier You · 饮食日记 iOS 应用及其支持服务（统称"服务"），不适用于服务中链接的第三方网站或服务。

如果你对本政策有疑问，请联系 **healthieryou.support@gmail.com**。

### 2. 我们收集的数据

我们只收集运营服务所必需的数据：

**账号信息**
- 邮箱地址（使用邮箱密码注册时）或 Apple Sign In 标识符
- 如果你选择通过 Apple Sign In 分享，可选的姓名信息

**个人资料**
- 年龄、生理性别、身高、体重
- 推算的 BMI 与 BMR（基础代谢率）

**餐次记录**
- 你上传供 AI 分析的餐次照片
- AI 生成的文本和结构化数据（食物名称、估算重量、热量区间）
- 你对餐次所做的编辑或备注
- 餐次记录的日期和时间

**每日活动**
- 你自行填写的每日运动消耗

**订阅状态**
- 是否有生效的订阅、当前产品、续费时间、Apple 原始交易 ID
- 我们不会接触你的信用卡或银行信息，支付由 Apple 处理

**反馈**
- 你通过反馈表单提交的自由文本，及其类型（问题或建议）

**运维日志**
- 维护和排错所需的标准服务器日志（时间戳、请求路径、错误信息）

我们不会收集位置信息、通讯录、浏览历史、广告标识符（IDFA）或设备传感器数据。

### 3. 如何使用这些数据

上述数据仅用于：
- 提供核心服务：AI 热量估算、餐次日记展示、统计、账号管理
- 管理订阅状态与权限
- 处理并回应你提交的反馈
- 运营与排错（服务器日志）
- 遵守法律义务

我们**不会**：
- 出售或出租你的数据
- 使用你的数据训练第三方 AI 模型
- 把你的数据用于广告或跨 App 追踪

### 4. 照片与 AI 处理

当你提交一张餐次照片进行分析时：
- 照片会上传至我们的服务器并转发给 OpenAI 的 API 进行分析
- OpenAI 返回识别出的食物项目和估算的热量区间
- 我们生成一张 256×256 的小缩略图供你在日记中查看
- 原始全分辨率照片在处理后不久即从活动存储中移除
- 我们不会将你的账号标识符或个人信息发送给 OpenAI；仅发送照片字节及其 API 所需的请求元数据

根据 OpenAI 的 Enterprise Privacy 承诺，OpenAI 不会保留通过其 API 提交的内容用于训练。第三方条款详见 [OpenAI Enterprise Privacy](https://openai.com/enterprise-privacy/)。

如果照片无法处理（网络错误、AI 失败或内容被拒），则不会创建餐次记录，也不会从你的账号中扣除免费次数。

### 5. 第三方服务

我们依赖以下处理者：

| 服务提供方 | 用途 | 共享的数据 |
| --- | --- | --- |
| Apple（App Store、StoreKit）| 账号登录（Sign in with Apple）、应用内购买 | 登录令牌、交易标识符 |
| Supabase | 账号认证、数据库、文件存储 | 上述全部账号、餐次、订阅数据 |
| OpenAI | AI 照片分析 | 仅餐次照片字节（不含账号标识符） |

各服务提供方在各自的隐私与安全承诺下代我们处理数据。

### 6. 数据留存

- **活跃账号数据**（个人资料、餐次、缩略图、订阅状态、反馈）在账号有效期内保存。
- **软删除的餐次** 立即从你的视图移除，并在 30 天内物理清除。
- **原始餐次照片** 在 AI 处理后不久从活动存储中移除。
- **账号删除** 会清除个人资料、餐次、缩略图、每日运动记录、反馈提交以及订阅状态。后台清理在合理时间内完成。
- **运维日志** 出于排错目的最长保留 90 天，到期自动滚出。

### 7. 你的选择

- **查看数据**：你的账号所有数据都可在应用内查看。
- **编辑餐次**：可以编辑任意已保存餐次的总热量估算。
- **删除餐次**：在日记中点选任意餐次 → 删除。
- **删除账号**：设置 → 账号 → 删除账号。此操作将永久删除你的数据，无法恢复。
- **管理订阅**：设置 → 订阅 → 管理订阅，会打开 Apple ID 系统订阅页面。

### 8. 未成年人隐私

Healthier You · 饮食日记 并非面向 13 岁以下儿童设计。我们不会有意收集 13 岁以下儿童的数据。如你认为有儿童创建了账号，请联系 **healthieryou.support@gmail.com**，我们将移除该账号。

### 9. 政策的变更

我们可能不时更新本政策。重大变更将反映在上方的"Last updated"日期处，必要时也会在应用内提示。

### 10. 联系方式

关于你的数据如有任何疑问、请求或担忧：
**healthieryou.support@gmail.com**
