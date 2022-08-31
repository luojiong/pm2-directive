# nodeJS  进程守护 PM2 使用方式
## 安装
` npm install -g pm2`

## 通过NPM命令启动服务
`pm2 start npm --name 你的进程名称 -- npm的命令 `
## 查看后台服务列表
`pm2 list `
## 删除后台服务
`pm2 delete  进程名称 `
## 停止后台服务
`pm2 stop  进程名称 `
