# Telegram 自动化机器人脚本，从多个 Telegram 帐户一次获取批量查询 ID！

此 Node.js 脚本可以管理多个 Telegram 帐户，适用于所有 Mini Apps 机器人，支持无限帐户，通过 Telegram 会话或 Telegram OTP 进行登录！使用 API ID 和 API HASH。该脚本还包括从所有帐户一次性获取查询 ID 的功能，并可同时处理多个 TG Mini Apps。然后，您可以在其他脚本中使用这些 Query_ID 来操作 Mini Apps。

# 如需任何帮助，请联系：Discord 上的 0xphatom https://discord.com/users/979641024215416842

# 操作步骤：

1. 克隆仓库 `git clone https://github.com/Solana0x/Query_Id.git`
2. 进入目录 `cd Query_Id`
3. 运行 `npm install`
4. 在 `index.js` 文件中添加 API ID 和 API HASH
5. 然后运行 `node index.js`
6. 您可以选择通过 `手机号码` 或 `Telegram 会话字符串` 登录。
7. 选择 `请求所有帐户的 WebView` 选项。
8. 输入 `请输入机器人对等体（例如：@YourBot）:`，在这里输入 Telegram 机器人的用户名，例如 `@blumCryptobot` 或 `@starmajorbot`。
9. 输入 `请输入 WebView URL:`，在这里输入 Telegram 机器人的推荐链接，例如 `https://t.me/blum/app?startapp=ref_4P0iHV9xlf`。
10. 按下回车后，您将在 TXT 文件中看到您的 QueryID，格式为 `Bot: @BlumCryptoBot | WebAppData: user=%7B%22id%22%3A6299188`。

# 获取 API ID 和 API HASH 的步骤

1. 登录 [https://my.telegram.org/auth](https://my.telegram.org/auth)
2. 创建一个新的 Telegram 应用程序，进入“API 开发工具”并填写表格。
3. 您可以参考这篇文章以获取帮助：[https://core.telegram.org/api/obtaining_api_id](https://core.telegram.org/api/obtaining_api_id)

仅限教育用途：

此脚本仅用于教育和研究目的。此项目的作者和贡献者对任何滥用此代码的行为不承担责任。使用此代码所采取的任何行动由用户自行承担责任。

# 版权声明：

此脚本受 1976 年《美国版权法》第 17 条的保护。未经授权复制或分发此脚本或其任何部分，可能导致严重的民事和刑事处罚，并将在法律的最大范围内予以起诉。有关更多信息，请查阅完整的法律文本：[美国法典第 17 条](https://www.copyright.gov/title17/)。
