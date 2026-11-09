# TCS Batch Query 隐私政策 / Privacy Policy

更新日期 / Last updated: 2026-11-09

开发者 / Developer: niehongbin0815@gmail.com

## 1. 适用范围

本政策适用于 TCS Batch Query（又称 TCS Query）浏览器扩展及其配套的查询、表格导出、飞书通知、可选豆包预判与内测授权服务。本产品是浏览器扩展，不是手机应用。

## 2. 处理哪些数据

- **查询和页面数据：** 用户输入的 TCS ID，以及支持的业务页面中与查询、提取有关的任务编号、需求编号、商品或直播间编号、案例信息、备注、链接、ASR 文本和相关接口返回内容。
- **导出和预判数据：** 用户选择导出的表格行、表格标识和链接；用户启动预判时提供的审核规则、选定 ASR、模型结果及回填状态。
- **账号与授权数据：** 启用相关功能时涉及的用户名、姓名、头像、邮箱、平台用户标识、OAuth 授权凭据、插件安装标识、内测资格、有效期及群成员状态。
- **本地运行数据：** 界面设置、查询和提取结果缓存、后台任务快照、进度及错误状态。
- **服务运行记录：** 配套服务为处理请求、权限核验、安全和故障排查产生的必要请求记录、时间、状态、错误信息和授权审计记录；服务平台也可能处理 IP 地址等网络日志。

扩展会在支持的业务页面读取必要的页面内容和相关请求、响应。它不以跟踪用户为目的收集无关网站的完整浏览历史。用户在平台或飞书的授权页面完成登录，扩展不要求用户将账号密码填写到扩展中。

## 3. 如何使用数据

数据仅用于实现或支持以下用户可见功能：批量查询与信息提取、表格创建和回读核对、向操作人发送完成通知、用户启动的豆包预判及结果回填、任务恢复、内测权限核验与用户同意的加群，以及这些功能的安全和故障处理。

普通查询或导出不会自动启动豆包预判。豆包预判须由用户启动；仅开启设置开关不会提交模型任务。

## 4. 数据传输与第三方

- 查询请求会发送到对应业务系统或查询服务。
- 导出数据会通过配套服务传输到飞书电子表格；操作人邮箱及必要的任务、表格信息会用于发送飞书卡片。
- 用户启动豆包预判后，选定的 ASR、审核规则及完成该请求所需的信息会经配套服务发送到豆包 Agent 服务，返回结果可写入所选表格。
- 账号授权、内测资格和用户同意的群成员管理由配套授权服务及飞书相关服务处理。

业务平台、飞书、豆包、服务托管平台和 GitHub 分别按其适用政策处理收到的数据。创建的飞书表格受其实际分享设置和所在组织权限控制，可能被该权限范围内的其他成员访问。请按需要调整表格分享权限。

我们不出售用户数据，不将其用于广告投放、广告画像或与扩展功能无关的营销。必要的数据传输限于提供上述功能、安全处理或履行法律义务。我们不在本政策中承诺第三方平台的独立数据保留或模型训练规则。

## 5. 数据保存与安全

界面设置、部分缓存、授权凭据和后台任务快照保存在浏览器扩展存储中；部分缓存仅保存在浏览器会话中。授权服务会保存账号、资格、群成员处理和必要审计信息。导出的表格与第三方会话由相应服务保存。

本地持久数据可能保留到用户清理扩展数据或卸载扩展。服务端记录的保留取决于完成服务、安全审计及适用要求所需的期限；本产品没有对所有数据统一设置“30 天后自动删除”。卸载扩展不会自动删除已创建的飞书表格或第三方会话。

扩展与配套服务的数据传输使用 HTTPS。账号授权通过平台授权流程完成；配套服务处理访问凭据，权限核验限制受控功能的使用。请同时保护浏览器个人资料、设备和组织账号。

## 6. 您的选择与删除请求

您可以选择不启动导出或豆包预判，停止进行中的预判，撤销相关平台授权，禁用或卸载扩展。删除扩展本地数据、飞书表格或第三方会话需分别在对应浏览器或服务中操作，并受您在该服务中的权限限制。

如需访问、更正或删除配套服务保存的账号资料，或有隐私问题，请联系 **niehongbin0815@gmail.com**。我们会在核验请求人身份后处理请求；依法或为必要安全审计需保留的数据可能无法立即删除。

## 7. 有限使用声明

TCS Batch Query 对通过扩展权限获取的用户数据的使用和传输遵守 Chrome Web Store 用户数据政策，包括有限使用要求。数据仅用于提供或改进本政策披露的扩展功能，不用于个性化、重定向或基于兴趣的广告。人工读取相关用户数据限于用户明确同意、必要安全处理、法律要求，或经聚合和匿名化后的内部运行分析。

## 8. 政策更新与联系

功能或数据处理方式发生变化时，我们会更新本页面并修改更新日期。隐私联系邮箱：**niehongbin0815@gmail.com**。

---

## English

### Scope

This policy applies to the TCS Batch Query browser extension, also called TCS Query, and its supporting query, spreadsheet export, Feishu notification, optional Doubao judgement, and beta authorization services. This product is a browser extension, not a mobile application.

### Data we handle

We handle IDs entered by the user and relevant content from supported business pages or their API responses, including task and requirement IDs, product or live-room IDs, case information, notes, links, and ASR text. Export and judgement features handle selected spreadsheet rows, sheet identifiers and links, user-provided review rules, selected ASR, model results, and write-back status.

When the associated features are enabled, account and authorization data may include username, name, avatar, email address, platform user identifier, OAuth credentials, extension installation identifier, beta eligibility and expiry, and group membership status. Local operation data includes settings, caches, background task snapshots, progress, and errors. Supporting services retain necessary request, authorization, security, and diagnostic records; hosting platforms may also process network logs such as IP addresses.

The extension reads the relevant page content and requests or responses needed for its disclosed features on supported business pages. It does not collect a complete history of unrelated websites for tracking. Users sign in through the platform or Feishu authorization page; the extension does not ask users to enter their account passwords into the extension.

### Purposes and transfers

Data is used for batch queries, extraction, spreadsheet creation and verification, notifications to the operator, user-initiated Doubao judgement and write-back, task recovery, beta eligibility checks, user-agreed group membership management, and necessary security or troubleshooting of those features.

Query requests are sent to the relevant business or query service. Export data is sent through the supporting service to Feishu Sheets; the operator's email and necessary task and sheet information are used for Feishu cards. When a user starts Doubao judgement, selected ASR, review rules, and information needed for that request are sent through the supporting service to the Doubao Agent service. Results may be written to the selected spreadsheet. Authorization and beta or group operations use the supporting authorization service and relevant Feishu services.

Business platforms, Feishu, Doubao, hosting providers, and GitHub handle received data under their applicable policies. Created spreadsheets are subject to their actual sharing settings and organization permissions; other people within that permitted scope may access them. Ordinary queries or exports do not automatically start Doubao judgement, and switching on its settings alone does not submit a model task.

We do not sell user data or use it for advertising, advertising profiles, or marketing unrelated to the extension. Transfers are limited to delivering the disclosed functions, necessary security, or legal obligations. This policy does not promise independent third-party retention or model-training rules.

### Storage, security, and choices

Settings, some caches, authorization credentials, and task snapshots are stored in browser extension storage. Some caches last only for the browser session. Supporting services retain account, beta, group-operation, and necessary audit information. Exported sheets and third-party sessions remain in their respective services.

Persistent local data may remain until the user clears extension data or uninstalls it. Server retention depends on service, security, audit, and applicable requirements; there is no universal automatic deletion after 30 days. Uninstalling the extension does not delete previously created sheets or third-party sessions. Data transfers use HTTPS, and authorization and permission checks protect controlled functions. Users should also protect their browser profile, device, and organization account.

Users can avoid starting exports or judgement, stop an ongoing judgement task, revoke platform authorization, and disable or uninstall the extension. Local data, Feishu sheets, and third-party sessions must be deleted separately in the relevant browser or service, subject to the user's permissions.

For access, correction, or deletion requests concerning supporting-service account data, or privacy questions, contact **niehongbin0815@gmail.com**. Requests are handled after identity verification; legal or necessary security-audit retention may prevent immediate deletion.

### Limited Use and policy updates

TCS Batch Query's use and transfer of user data obtained through extension permissions complies with the Chrome Web Store User Data Policy, including its Limited Use requirements. Data is used only to provide or improve disclosed extension features, never for personalized, re-targeted, or interest-based advertising. Human access is limited to explicit user consent, necessary security, legal requirements, or aggregated and anonymized internal operations.

We update this page and its date when the functionality or data practices change. Contact: **niehongbin0815@gmail.com**.
