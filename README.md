# nonebot_plugin_wolfram

适用于 [Nonebot2](https://github.com/nonebot/nonebot2) 的多功能计算器插件。

## 安装

1. - 方法1：**[暂不支持]** 通过 `pip` 或 `nb` 安装
   - 方法2：clone 该项目，手动放到 bot 的插件目录下

3. 在 `.env` 文件中配置 `WOLFRAM_API_KEY`

```
WOLFRAM_API_KEY = "your-wolfram-api-key"
```

- API Key 的获取方式见 https://products.wolframalpha.com/api/

## 功能

- 从 [Wolfram|Alpha](https://www.wolframalpha.com/) 处获取指定问题的答案，会发送一张图片。
- 从 [Wolfram|Alpha](https://www.wolframalpha.com/) 处获取指定问题的简短文字回答。

## 命令

1. 获取答案图片：`calc <问题>`，可换行输入。
2. 获取简短回答：`tellme <问题>`，可换行输入。
