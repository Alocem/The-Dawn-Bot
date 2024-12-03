# 🌅 Dawn扩展机器人 [v1.6]

<div align="center">
  <img src="./console/images/console.png" alt="黎明扩展机器人控制台" width="600"/>
  
  <p align="center">
    <a href="https://t.me/xuegaoz">
      <img src="https://img.shields.io/badge/Telegram-Channel-blue?style=for-the-badge&logo=telegram" alt="Telegram 频道">
    </a>
    <a href="https://t.me/+FZHZVA_gEOJhOWM1">
      <img src="https://img.shields.io/badge/Telegram-Chat-blue?style=for-the-badge&logo=telegram" alt="Telegram 聊天">
    </a>
  </p>
</div>

## 📋 目录
- [功能](#-功能)
- [需求](#-需求)
- [安装](#-安装)
- [配置](#️-配置)
- [使用](#-使用)
- [故障排除](#-故障排除)

## 🚀 功能

- ✨ **账户管理**
  - ✅ 自动账户注册和登录
  - 📧 智能账户重新验证系统
  - 🛡️ 基于令牌的身份验证存储
  
- 🤖 **自动化**
  - 🌾 智能任务完成
  - 💰 优化的积分获取
  - 🔄 高级保活系统
  
- 📊 **分析与导出**
  - 📈 全面的账户统计
  - 📉 被封禁账户跟踪
  - 📋 未验证账户监控
  
- 🔒 **安全**
  - 🧩吉| 科尔沁左翼中旗| 河池| 安西| 石台| 平湖| 金川| 盐山| 义县| 望江| 长治市| 祁东| 祁门| 平和| 永济| 旅顺口| 平湖| 阜新市| 安顺| 旬邑| 永靖| 乌拉特中旗| 孟津| 余干| 郎溪| 宿州| 富锦| 临澧| 乌马河| 阿瓦提| 长治市| 阿图什| 五原| 福安| 泾阳  1.0.0  2015-12-27
 * @version 1.0.0 2015-12-27
 * @param {string}  str 需要进行base64解码的字符串
 * @return {string} 解码后的字符串
 */
function decode(str) {
    return decodeURIComponent(escape(window.atob(str)));
}
```

## ⚠️ 重要提示

- 🕒 推荐的保活间隔：120秒
- 📧 Gmail 用户：请使用应用专用密码
- 🔄 未验证的账户可以使用注册模块重新验证
- 💾 授权令牌存储在本地数据库中
- 🤖 需要外部验证码服务 (2captcha/anticaptcha)

## 🔧 故障排除

### 常见问题及解决方案

#### 📧 邮件验证失败
- 验证 settings.yaml 中的 IMAP 设置
- 检查电子邮件提供商的安全设置
- 确保 Gmail 使用应用专用密码

#### 🧩 验证码问题
- 验证 API 密钥是否有效
- 检查服务余额
- 确保所选服务正常运行

#### 🌐 代理问题
- 验证代理格式
- 检查代理功能
- 确保代理身份验证正确

## 📞 支持

加入我们的 Telegram 社区获取支持:
- 📢 频道: [JamBitPY](https://t.me/xuegaoz)
- 💬 聊天: [JamBitChat](https://t.me/+FZHZVA_gEOJhOWM1)
