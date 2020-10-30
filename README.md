# Ming's Running Page

> 通过定时任务自动抓取跑步 App 数据，数据可视化后部署到 Vercel 上

### 如何部署

1. Fork 仓库
2. 设置环境变量
   1. 获取跑步 App Token
   2. 获取 GitHub Token
3. 配置 [GitHub Workflow](./.github/workflows/run_data_sync.yml)]
   1. 配置 App 类型为 `nike`
   2. 配置仓库密钥 `NIKE_REFRESH_TOKEN`
   3. 配置仓库 Git 读写密钥 `GIT_TOKEN`
4. 部署到 Vercel
5. 配置个性域名 (可选)


### 特别感谢

- [@yihong0618](https://github.com/yihong0618)
