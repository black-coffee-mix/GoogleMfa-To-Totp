# Google MFA 转 TOTP 工具使用手册 | Google MFA to TOTP Tool User Guide
纯本地运行 | 无联网 | 无数据上传 | 全设备兼容
Local Only | No Internet | No Data Upload | Cross-device Support

---

## 工具介绍 | Introduction
将 Google 身份验证器导出的 MFA 迁移数据，解析为标准 TOTP 格式，可直接导入 Bitwarden 使用。
Convert Google Authenticator MFA migration data to standard TOTP format for direct import into Bitwarden.

## 核心功能 | Core Features
- 双模式输入：摄像头扫码 / 粘贴迁移链接
  Dual Input: Camera Scan / Paste Migration Link
- 批量解析所有 MFA 账号
  Batch parse all MFA accounts
- 生成 TOTP 二维码 + 密钥
  Generate TOTP QR code + Secret Key
- 支持 Mac / Windows / iPhone / 安卓
  Support Mac / Windows / iPhone / Android

---

## 准备工作 | Preparation
1. 打开 Google 身份验证器
   Open Google Authenticator
2. 右上角 ⋮ → 转移账户 → 导出账户
   Tap ⋮ → Transfer accounts → Export accounts
3. 验证身份，生成官方迁移二维码
   Verify identity and generate official migration QR code

---

## 使用方法 | Usage

### 方式 1：电脑端（Mac/Windows）| PC (Mac/Windows)
1. 用 Chrome / Edge 打开 HTML 工具
   Open HTML tool with Chrome / Edge
2. 选择 摄像头扫码
   Select Camera Scan
3. 开启摄像头 → 允许权限
   Start Camera → Allow permission
4. 扫描 Google 迁移二维码
   Scan Google migration QR code
5. 自动生成 TOTP 数据
   Auto-generate TOTP data

### 方式 2：手机端（推荐）| Mobile (Recommended)
1. 将 HTML 文件传到手机
   Transfer HTML file to mobile
2. 用 Chrome 浏览器打开
   Open with Chrome browser
3. 直接扫码解析
   Scan and parse directly
4. 导入 Bitwarden
   Import to Bitwarden

### 方式 3：粘贴链接 | Paste Link
1. 复制 otpauth-migration:// 开头的链接
   Copy link starting with otpauth-migration://
2. 粘贴到工具输入框
   Paste into tool input box
3. 点击解析
   Click Parse

---

## Bitwarden 导入教程 | Bitwarden Import Guide
1. 打开 Bitwarden → 编辑对应账号
   Open Bitwarden → Edit account
2. 找到 双因素认证 (2FA/MFA)
   Find Two-factor Auth (2FA/MFA)
3. 二选一：
   Choose one:
   - 扫码导入 Scan QR code
   - 复制密钥粘贴 Paste secret key
4. 保存完成
   Save and finish

---

## 常见问题 | FAQ
### 未找到可用数据 | No valid data found
- 仅扫描 Google 官方导出的迁移二维码
  Only scan official Google migration QR code

### 摄像头无法开启 | Camera failed
- 使用 Chrome / Edge 浏览器
  Use Chrome / Edge browser
- 允许摄像头权限
  Allow camera permission

### 解析失败 | Parse failed
- 重新扫码 / 重新粘贴链接
  Rescan / Repaste link
- 确认是 Google 官方数据
  Confirm it's Google official data

---

## 安全声明 | Security
- 全程本地运行，无任何网络请求
  100% local, no network requests
- 数据不上传、不同步、不泄露
  No data upload, sync or leak
- 开源纯前端代码，安全可控
  Open-source frontend code, safe and secure
