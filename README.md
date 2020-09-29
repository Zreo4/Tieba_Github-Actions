# 利用Github Actions自动签到百度贴吧

![Run it on action](https://github.com/bruceCzK/Tieba_Github-Actions/workflows/Run%20it%20on%20action/badge.svg)

1. Fork此仓库
2. 获取 BDUSS：登录百度后在 Cookie 中找到名为 `BDUSS` 的条目，复制内容
3. 在 Settings -> Secrets 添加一个名为 `BDUSS` 的变量，粘贴刚才的内容
4. 在 Actions 运行一次 workflow
