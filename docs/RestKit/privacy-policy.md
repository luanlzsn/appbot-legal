# 隐私政策 / Privacy Policy — RestKit / 眠报本

> 运营者与联系邮箱已填写（与 App Store 卖家及既有 appbot-legal 应用一致）。请把本页 HTTPS URL 填入 App Store Connect 与应用内设置。  
> **诚实声明**：无自建业务后端；睡眠数据经 **HealthKit 只读** 在设备上读取；周报与日记为本地康养台账，**非医疗器械**；购买收据由 Apple 处理；家人共享当前为本机快照 + 系统分享（完整 CloudKit Share 尚未上线）；**未接入**第三方分析/广告 SDK。  
> **不要**在页脚或正文添加未取得的合规徽章。本文不构成法律意见。

---

**生效日 / Effective date:** 2026-11-03  
**产品 / Product:** RestKit（中文名：眠报本）  
**运营者 / Operator:** Lisha Gan  
**联系 / Contact:** luanlzsn@gmail.com

本页同时提供中文与英文；若解释冲突，以你分发地区适用法律及你与用户之间的约定为准。

---

## 中文

### 1. 我们是谁

眠报本（RestKit）是一款帮助你在**设备上**记录睡眠周报、仪式与醒来笔记的 iOS 康养台账应用。我们**不运营用于存储你睡眠或日记内容的自建业务服务器**，也**不提供诊疗、处方或远程监护服务**。本应用**不是医疗器械**，不用于诊断、治疗或预防任何疾病。

### 2. 我们收集哪些信息

就开发者可控的「收集并传到开发者服务器」而言：**我们基本上不收集你的个人信息或健康明细。**

| 数据 | 说明 |
|------|------|
| Apple Health 睡眠分析（只读） | 仅在你授权后，通过 **HealthKit 只读** 在设备上读取睡眠样本以填充台账。开发者不运营可拉取这些数据的自建后台。 |
| 你创建的周报、仪式、笔记、目标与偏好 | 保存在**你的设备本地**（如 SwiftData）。开发者**无法**像运营自建后台那样常规读取这些内容。 |
| 可选家庭共享快照 | **当前版本**生成只读周报摘要，并通过**系统分享面板**发送；**不是**完整 CloudKit 多人共享链路。不会把原始 Health 导出打包发出。 |
| 小组件桥接（可选） | 通过 App Group 在本机主应用与小组件间共享摘要字段；不离开你的设备。 |
| 应用内购买 | 终身 Pro 等交易由 **Apple StoreKit** 处理。我们通过 StoreKit 获知是否已解锁权益，**不单独收集银行卡号**。 |
| 诊断与分析 | **未接入**第三方广告或分析 SDK。 |
| 账号 | **无**开发者自建账号体系。 |

我们**不会**为提供核心功能而：出售你的睡眠或日记内容、用你的数据做跨 App 追踪广告、或建立公共健康社交资料。

### 3. 我们如何使用信息

在设备本地，数据仅用于：展示睡眠台账与周报、仪式提醒、醒来笔记、小组件摘要、按你的操作导出/系统分享，以及根据 Apple 提供的购买状态解锁 Pro。

### 4. 共享与第三方

- **Apple**：App Store、StoreKit、HealthKit、（若你使用系统分享）系统分享面板等基础设施。  
- **我们不向广告商出售个人信息。**  
- 法律要求或为保护权利所必需时，可能在法律允许范围内披露；因无自建业务库存储你的健康正文，实际可披露范围通常极为有限。

### 5. 数据保留与删除

- 本地数据：你可在应用内删除条目或清空相关内容；卸载应用通常会删除设备上的应用数据（以系统行为为准）。  
- HealthKit 中的睡眠样本由 Apple Health / 你的设备保管；撤销授权后应用不再读取。  
- Pro 权益与 Apple 账户购买记录相关联；恢复购买依赖你的 Apple ID。

### 6. 儿童

本应用未专门面向儿童设计。请由监护人合理管理设备与 Apple ID。

### 7. 你的选择

- 可拒绝 HealthKit 授权；未授权时仍可进行手动日记与仪式记录，自动睡眠填充不可用。  
- 可不购买 Pro，在免费限额内使用。  
- 可通过系统「健康」与「设置」管理权限。

### 8. 国际用户

App Store 由 Apple 在全球基础设施上运营。我们不另设自建跨国业务数据库存放你的睡眠或日记内容。

### 9. 政策更新

我们可能更新本政策。更新后会在本页调整生效日；若变更对你有重大影响，我们将在合理范围内通过应用内说明或 App Store 产品页等方式提示（如适用）。

### 10. 联系我们

关于隐私问题，请发送邮件至：**luanlzsn@gmail.com**。

---

## English

### 1. Who we are

RestKit is an on-device wellness sleep ledger for weekly reports, rituals, and wake notes. We **do not operate a custom backend** that stores your sleep or journal content, and we **do not provide diagnosis, prescriptions, or remote monitoring**. RestKit is **not a medical device** and is not intended to diagnose, treat, or prevent any disease.

### 2. What we collect

For data the developer controls and sends to a developer server: **we essentially do not collect your personal information or health details.**

| Data | Notes |
|------|------|
| Apple Health sleep analysis (read-only) | Only with your permission, via **HealthKit read-only** on device to fill your ledger. We do not run a backend that can pull this data. |
| Weekly reports, rituals, notes, goals, preferences | Stored **locally on your device** (e.g. SwiftData). The developer cannot routinely read them like a custom backend would. |
| Optional family-share snapshot | **Current version** prepares a read-only weekly summary and uses the **system share sheet**. This is **not** a full CloudKit multi-user share pipeline. Raw Health dumps are not packaged for sending. |
| Widget bridge (optional) | App Group fields shared on-device between the app and widgets; they do not leave your device. |
| In-app purchases | Lifetime Pro and similar are processed by **Apple StoreKit**. We learn unlock status only; we do **not** collect card numbers. |
| Analytics / ads | **No** third-party advertising or analytics SDK. |
| Accounts | **No** developer-operated account system. |

We do **not** sell your sleep or journal content, use it for cross-app tracking ads, or run a public health social graph for core features.

### 3. How we use information

On device only: sleep ledger and weekly reports, rituals, wake notes, widget summaries, export/system share you initiate, and Pro unlock based on Apple purchase status.

### 4. Sharing and third parties

- **Apple**: App Store, StoreKit, HealthKit, and (if you use it) the system share sheet.  
- **We do not sell personal information to advertisers.**  
- We may disclose information when legally required or to protect rights, within applicable law; without a custom business database of your health content, practical disclosure scope is usually very limited.

### 5. Retention and deletion

- Local data: delete entries in-app; uninstalling typically removes app data (per system behavior).  
- HealthKit sleep samples remain under Apple Health / your device; revoking permission stops further reads.  
- Pro entitlements follow your Apple ID; use Restore Purchases as needed.

### 6. Children

Not directed at children. Guardians should manage devices and Apple IDs appropriately.

### 7. Your choices

- Decline HealthKit; manual journaling and rituals still work without auto sleep fill.  
- Stay on free limits without buying Pro.  
- Manage permissions in system Health and Settings.

### 8. International users

The App Store runs on Apple’s global infrastructure. We do not operate a separate cross-border business database of your sleep or journal content.

### 9. Changes

We may update this policy and the effective date on this page. For material changes we will provide reasonable notice in-app or via the product page where applicable.

### 10. Contact

**luanlzsn@gmail.com**
