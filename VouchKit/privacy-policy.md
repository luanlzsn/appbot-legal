# 隐私政策 / Privacy Policy — VouchKit / 券本

> 可直接托管为静态 HTML/Markdown 页（见同目录 `README.md` 的 GitHub Pages 说明）。  
> 运营者与联系邮箱已填写（与 App Store 卖家及既有 playku-legal / WeRenew 一致）。请把本页 HTTPS URL 填入 App Store Connect 与应用内设置。  
> **诚实声明**：无自建业务后端；不连接商户查余额；不接银行；购买收据由 Apple 处理。  
> **不要**在页脚或正文添加未取得的合规徽章（如虚假 ISO/SOC/「已认证 GDPR」印章）。遵守适用法律是运营者责任，本文不构成法律意见。

---

**生效日 / Effective date:** 2026-10-30  
**产品 / Product:** VouchKit（中文名：券本）  
**运营者 / Operator:** Lisha Gan  
**联系 / Contact:** luanlzsn@gmail.com

本页同时提供中文与英文；若解释冲突，以你分发地区适用法律及你与用户之间的约定为准；中文为主市场时可优先中文表述。

---

## 中文

### 1. 我们是谁

券本（VouchKit）是一款帮助你**手动记录**礼品卡、优惠券与兑换码、查看余额与到期日、全屏出示条码，并设置到期本地提醒的 iOS 应用。我们**不运营用于存储你卡券内容的自建业务服务器**，也**不连接商户系统查询真实余额**，更**不提供银行账户或银行卡连接**。

### 2. 我们收集哪些信息

就开发者可控的「收集并传到开发者服务器」而言：**我们基本上不收集你的个人信息或卡券明细。**

| 数据 | 说明 |
|------|------|
| 你输入的卡券内容（商家、类型、余额、到期日、卡号/券码、PIN、备注、可选本地照片等） | 保存在**你的设备本地**（如 SwiftData）。开发者**无法**像运营自建后台那样常规读取这些内容。 |
| 本地通知相关 | 到期提醒由系统在设备上调度；我们不通过自建推送服务器发送营销推送。 |
| 应用内购买 | 终身 Pro 等交易由 **Apple** 处理。我们通过 StoreKit 获知你是否已解锁权益（如交易校验结果/权益状态），**不单独收集并保存你的银行卡号**。收据与支付详情以 Apple 账户体系为准。 |
| 诊断与分析 | MVP **未接入**第三方广告或分析 SDK。若日后系统（如你自愿通过系统对话框）向 Apple 分享诊断数据，该等处理适用 Apple 的政策，而非我们自建收集。 |
| 账号 | **无**开发者自建账号体系；你无需向我们注册用户名密码。 |

我们**不会**为提供核心功能而：连接商户查询余额、连接你的银行、读取你的邮箱以「发现」卡券、出售你的卡券清单，或用你的数据做跨 App 追踪广告（MVP 无追踪、无广告 SDK）。

### 3. 我们如何使用信息

在设备本地，数据仅用于：展示卡券清单与余额、生成/出示条码、调度本地到期提醒、记录余额变更流水，以及根据 Apple 提供的购买状态解锁 Pro 功能。

### 4. 共享与第三方

- **Apple**：提供 App Store、StoreKit 支付、系统通知等基础设施。相关处理受 Apple 隐私政策与你的系统设置约束。  
- **我们不向广告商出售个人信息。**  
- 法律要求或为保护权利所必需时，可能在法律允许范围内披露（例如响应有管辖权的合法要求）。因我们无自建业务库存储你的卡券正文，实际可披露范围通常极为有限。

### 5. 数据保留与删除

- 本地数据：你可在应用内删除条目；卸载应用通常会删除设备上的应用数据（以系统行为为准）。  
- Pro 权益状态与 Apple 账户购买记录相关联；恢复购买依赖你的 Apple ID。

### 6. 儿童

本应用面向一般消费者管理礼品卡与优惠券，未专门面向儿童设计。若你是监护人，请合理管理设备与 Apple ID。

### 7. 你的选择

- 可拒绝通知权限，应用仍可使用（无到期提醒）。  
- 可不购买 Pro，在免费 5 张未归档卡限额内使用。  
- 可通过系统设置管理通知与屏幕时间等。

### 8. 国际用户

App Store 由 Apple 在全球基础设施上运营。我们不另设自建跨国业务数据库存放你的卡券内容。

### 9. 政策更新

我们可能更新本政策。更新后会在本页调整生效日；若变更对你有重大影响，我们将在合理范围内通过应用内说明或 App Store 产品页等方式提示（如适用）。

### 10. 联系我们

关于隐私问题，请发送邮件至：**luanlzsn@gmail.com**。

---

## English

### 1. Who we are

VouchKit (Chinese name: 券本) is an iOS app that helps you **manually** store gift cards, coupons, and promo codes, track balances and expiry dates, present barcodes full-screen, and schedule local expiry reminders. We **do not operate a custom business backend** that stores your voucher contents, **do not connect to merchants to look up real balances**, and **do not connect to banks or card feeds**.

### 2. What we collect

Regarding information the developer collects onto developer-operated servers: **we essentially collect little to none.**

| Data | Details |
|------|---------|
| Vouchers you enter (merchant, type, balance, expiry, code, PIN, notes, optional local photo) | Stored **on your device** (e.g. SwiftData). We do not routinely read that content via a developer backend. |
| Local notifications | Scheduled on-device; we do not run our own push/marketing notification server for MVP. |
| In-App Purchases | Handled by **Apple**. We learn whether you unlocked Pro via StoreKit (entitlement / verified transactions). We do **not** collect your card number ourselves. |
| Analytics / ads | MVP includes **no** third-party ad or analytics SDK. |
| Accounts | **No** developer-operated user accounts. |

We do **not**, for core features: query merchant balances, link your bank, scrape your email to discover vouchers, sell your list, or track you across apps for ads (no tracking / ad SDK in MVP).

### 3. How we use information

On-device: to show your voucher wallet, generate/present barcodes, schedule local expiry reminders, keep balance history, and unlock Pro based on Apple purchase state.

### 4. Sharing and third parties

- **Apple**: App Store, StoreKit, system notifications—subject to Apple’s policies and your settings.  
- We do **not** sell personal information to advertisers.  
- We may disclose information if required by law or to protect rights, to the limited extent anything is available to us (typically minimal without a content backend).

### 5. Retention and deletion

Delete items in-app; uninstalling usually removes on-device app data (per OS). Pro is tied to your Apple ID purchases; use Restore Purchases as needed.

### 6. Children

Not directed at children. Guardians should manage devices and Apple IDs appropriately.

### 7. Your choices

Deny notifications; stay on the free 5 unarchived-voucher tier; manage notifications in system Settings.

### 8. International users

Apple operates App Store infrastructure; we do not maintain a separate developer database of your voucher contents.

### 9. Changes

We may update this policy and the effective date on this page; material changes may also be noted in-app or on the product page where appropriate.

### 10. Contact

Privacy questions: **luanlzsn@gmail.com**. Operator: **Lisha Gan**.

---

## 托管提示（非政策正文）

1. 按 `legal/README.md` 用 GitHub Pages 发布本文件（建议路径 `/VouchKit/privacy`）。  
2. 运营者 / 联系邮箱已写入（Lisha Gan / luanlzsn@gmail.com）。  
3. App Store Connect 与应用内隐私 URL 必须指向**已上线** HTTPS 页面。  
4. App Store「App 隐私」问卷勾选结果须与本文一致。  
