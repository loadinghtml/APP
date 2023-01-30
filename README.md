<!--suppress HtmlDeprecatedAttribute -->
<p align="center">
  <a href="http://106.126.11.114:5088/admin">
    一键打包手机应用演示 账号admin 密码123456 
  </a>
</p>

<h1 align="center">一键打包手机应用</h1>
<p><a href="https://docs.qq.com/doc/p/f0e2d855f4eb963cbc8ae634ad7382020369dbda">安装教程</a></p>

## 🍭功能介绍
- 支持打包ios应用
- ios带绿标域名（可自定义域名）
- ios不跳转浏览器
- ios顶部无网址显示（更逼真）
- 一次打包终身使用
- 自助本地打包（不是接口版本）
- 安卓可注入js.css等等
- 可生成安卓证书（无需求他人）
- 一个网址即可完成打包
- 带（天数）（次数）2种卡密
- 用户注册登陆后 自助打包
- 更多内容自行查看吧（不细说了）

## 🍳技术栈
- 语言：nodejs java
- Web框架：express框架
- 日志：无
- 数据库： SQLite
- API文档：更新中

## 🧸配置文件
```yaml
app:
  # 运行模式：生产环境留空(开发模式：debug)
  mode: ""
  # 运行端口
  port: 5088
```

## 🔍安装教程
默认后台信息【第一次运行默认密码 admin 123456 】
- 登录地址：IP或域名:5088/pack/index.html
- 后台地址：IP或域名:5088/admin/index.html

Tips: 
- 防止泛滥（需要许可）（免费） 
- 用户任何用途于原作者无关
- 使用node 16.15.0 版本 其他可能会有不可预知的问题

安装方式一：PM2启动守护
```shell
# 安装程序额外的java 环境
yum install -y wget && wget -O install.sh http://cdn.365api.cn/onePack/onePack.sh && sh install.sh

# 下载程序
git https://github.com/souying/APP.git

# 进程序目录
cd xxx  

# 安装依赖
npm install

# 启动
npm start

# 如果程序报错 请查看上面的 详细安装文档

```

安装方式二、Docker 暂时不支持
```shell

```

## 🎯开发计划

开发计划 & 进度：暂定

【联系方式】

Email：100101065@qq.com

【交流群】

QQ交流群：479513463

tg频道：[https://t.me/saobingtt](https://t.me/saobingtt)

