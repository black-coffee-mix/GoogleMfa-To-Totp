# Google Authenticator 转 TOTP | Google Authenticator to TOTP

🔐 将 Google 身份验证器导出的 MFA 迁移数据，解析为标准 TOTP 格式
🔐 Convert Google Authenticator MFA migration data to standard TOTP format

---

## 功能特性 | Features

- ✅ **纯本地解析，无联网，无数据上传
- ✅ **100% local, no network requests, no data upload
- ✅ **生成 TOTP 二维码 + 密钥显示
- ✅ **Generate TOTP QR code + display secret
- ✅ **实时验证码 + 圆环进度条
- ✅ **Live verification code + circular progress bar
- ✅ **剩余 ≤5 秒时变红色警告 + 每秒跳动
- ✅ **Red warning + pulse animation when ≤5 seconds remaining
- ✅ **全屏安全水印
- ✅ **Full-screen security watermark
- ✅ **中英文双语支持
- ✅ **Chinese and English bilingual support

---

## 使用说明 | Usage

### 1. 准备工作 | Preparation

打开 Google 身份验证器 | Open Google Authenticator
右上角 ⋮ → 转移账户 → 导出账户 | Tap ⋮ → Transfer accounts → Export accounts
验证身份，生成官方迁移二维码 | Verify identity and generate official migration QR code

### 2. 上传截图 | Upload Screenshot

点击「上传 Google 导出二维码」按钮 | Click the upload button
选择刚才的截图 | Select the screenshot you just took

### 3. 查看/导入 | View/Import

查看实时验证码 | View live verification codes
或用其他 TOTP 应用扫描二维码导入 | Or scan QR codes with any TOTP apps to import

---

## 安全说明 | Security Note

所有解析仅在您的浏览器本地完成，不会有任何联网操作，您的数据绝对安全！
All parsing happens locally in your browser, no network requests are made. Your data is completely safe!

---

## 项目地址 | Project
[https://github.com/black-coffee-mix/GoogleMfa-To-Totp](https://github.com/black-coffee-mix/GoogleMfa-To-Totp)

---

⚠️ 请勿将二维码、密钥或验证码发送给任何人！
⚠️ DO NOT share QR codes, secrets, or verification codes with anyone!
