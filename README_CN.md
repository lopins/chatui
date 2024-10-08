<div align="right">
   <strong>中文</strong> | <a href="README.md">English</a>
</div>
<div align="center">
<h1>Chat UI</h1>
<p>Chat UI: 使用单个HTML文件为AI对话构建整个前端UI</p>
</div>

# Chat UI

聊天界面变得越来越复杂，通常包含整个前端项目及其部署解决方案。 

本仓库旨在使用单个HTML文件构建整个前端UI，目标是以极简主义方法创建一个聊天机器人。 

通过简化结构和关键功能，开发人员可以快速设置并实验功能性聊天机器人，遵循精简项目设计的理念。 

## 如何使用 

### 选项 1: 访问演示 [AIQL](https://chat.aiql.com/) 

> 演示默认使用 `Qwen 2.5` 

### 选项 2: 下载 [Index](./index.html) 并本地打开（推荐） 

### 选项 3: 使用 [Docker](https://hub.docker.com/repository/docker/aiql/chat-ui/tags?page=1&ordering=last_updated) 部署自己的聊天机器人 

``` shell
docker run -p 8080:8080 -d aiql/chat-ui 
``` 

### 选项 4: 叉此仓库并将其链接到 [Cloudflare 页面](https://developers.cloudflare.com/pages) 

- 演示 <https://www2.aiql.com> 

## 如何配置 

默认情况下，聊天机器人将使用与OpenAI Chatgpt相同的API格式。您可以插入您的OpenAI `API Key` 并直接使用它。 

或者更改配置中的 `Endpoint` 以使用其他供应商的API 

> 您可以从 [示例](./example/config) 下载配置模板，并使用它进行快速配置 

## 故障排除 

如果您在打开页面时遇到问题，而简单的刷新无法解决问题，请按照以下步骤操作： 

1. 右键点击浏览器页面并转到 `Network` 部分。 

2. 右键点击表格部分，清除浏览器的缓存和cookie，以确保您拥有页面的最新版本。 

3. 此外，检查浏览器的网络部分，查看由于您的位置哪些资源未能加载。这将为您提供关于问题的更具体信息。 

## 演示 

![](./demo.gif)