# koishi-plugin-wolfram-alpha
 
[![npm](https://img.shields.io/npm/v/koishi-plugin-wolfram-alpha?style=flat-square)](https://www.npmjs.com/package/koishi-plugin-wolfram-alpha)

调用 [Wolfram Alpha](https://www.wolframalpha.com/) 查询。

你需要申请一个 Wolfram App 并配置 `appid` 以开启本功能。

## 如何申请

1. 前往 https://products.wolframalpha.com/api/
2. 点击 Get API Access，按照指引完成操作即可获得 App ID
3. 每个月的免费调用额度为 2000 次

## 配置项

### appid

- 类型: string

Wolfram Alpha App ID。

## 指令：alpha

- 基本语法：`alpha <expr>`
- 选项列表：
  - `-f, --full` 显示完整回答
