# 极简朋友圈


又开了个新坑,[极简论坛](https://discussion.mblog.club/),可以过来用于讨论[极简朋友圈](https://github.com/kingwrcy/moments),[极简博客](https://dev.mblog.club)的社区,当然代码也[开源](https://github.com/kingwrcy/discussion)了,可以自由部署使用,有问题可以上论坛反馈.

[重写了多人版朋友圈](https://m.hotnews.pw) -基于世界上最好的编程语言php编写的demo,目前还不完善,有需要的可以看看.

[极简分享](https://hotnews.pw) - 基于golang的分享社区,镜像包只有6mb.



[![docker pull](https://img.shields.io/badge/moments-更新记录-blue)](https://github.com/kingwrcy/moments/blob/master/release.md)
[![docker pull](https://img.shields.io/badge/moments-常见问题-blue)](https://github.com/kingwrcy/moments/blob/master/q&a.md)
![moments github action status](https://img.shields.io/github/actions/workflow/status/kingwrcy/moments/deploy.yml)
[![docker pull](https://img.shields.io/docker/pulls/kingwrcy/moments)](https://hub.docker.com/repository/docker/kingwrcy/moments)
[![docker pull](https://img.shields.io/badge/Telegram-group-blue)](https://t.me/simple_moments)
[![docker pull](https://img.shields.io/badge/1panel-本地安装-blue)](https://ono.ee/?p=1713750155422)


[社区版用户版本](https://moments.randallanjie.com/),由[网友](https://github.com/RandallAnjie)自行fork修改而成.本体目前不支持多用户.

有需要的可以看看,目前已经开放注册.


## 贡献者 ✨

感谢这些贡献代码的朋友

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/RandallAnjie"><img src="https://avatars.githubusercontent.com/u/84122428?v=4?s=80" width="80px;" alt="Randall"/><br /><sub><b>Randall</b></sub></a><br /><a href="https://github.com/kingwrcy/moments/commits?author=RandallAnjie" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Jonnyan404"><img src="https://avatars.githubusercontent.com/u/20352705?v=4?s=80" width="80px;" alt="jonny"/><br /><sub><b>jonny</b></sub></a><br /><a href="https://github.com/kingwrcy/moments/commits?author=Jonnyan404" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/akarikun"><img src="https://avatars.githubusercontent.com/u/11921182?v=4?s=80" width="80px;" alt="明"/><br /><sub><b>明</b></sub></a><br /><a href="https://github.com/kingwrcy/moments/commits?author=akarikun" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/douseful"><img src="https://avatars.githubusercontent.com/u/52767905?v=4?s=80" width="80px;" alt="yee"/><br /><sub><b>yee</b></sub></a><br /><a href="https://github.com/kingwrcy/moments/commits?author=douseful" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.jschef.com/"><img src="https://avatars.githubusercontent.com/u/38160059?v=4?s=80" width="80px;" alt="Chef"/><br /><sub><b>Chef</b></sub></a><br /><a href="https://github.com/kingwrcy/moments/commits?author=Chef5" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://xwsir.cn/"><img src="https://avatars.githubusercontent.com/u/17978673?v=4?s=80" width="80px;" alt="小王先森"/><br /><sub><b>小王先森</b></sub></a><br /><a href="https://github.com/kingwrcy/moments/commits?author=dinphy" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.gooth.org/"><img src="https://avatars.githubusercontent.com/u/126313?v=4?s=80" width="80px;" alt="Athurg Gooth"/><br /><sub><b>Athurg Gooth</b></sub></a><br /><a href="https://github.com/kingwrcy/moments/commits?author=athurg" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

***从v0.2版本起,这个环境变量必填,不填无法正常使用.***
```
-- 自定义jwt密钥(从0.2版本开始必填,不填无法使用)
NUXT_JWT_KEY=自定义jwt密钥,可以自己随机生成
```


## S3配置教程

[![docker pull](https://img.shields.io/badge/CF-R2配置-blue)](https://jerry.mblog.club/moments-r2-config)
[![docker pull](https://img.shields.io/badge/阿里云-OSS配置-blue)](https://jerry.mblog.club/moments-config-aliyun)


S3兼容的对象存储配置方法(不是必须的,只有你需要把图片存储到对象存储时才需要配置,默认图片存在本地,可备份):


又拍云 不支持[使用预签名 URL 上传对象](https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/userguide/PresignedUrlUploadObject.html),所以不支持又拍云.


[在线DEMO](https://m.mblog.club),欢迎体验.目前不支持多用户,多用户版本已由[RandallAnjie](https://github.com/RandallAnjie)自行实现了,有需要的可以去[看看](https://moments.randallanjie.com/)

[1panel本地安装](https://ono.ee/?p=1713750155422),感谢[包子叔](https://ono.ee)提供的教程.

- 支持匿名评论/点赞
- 支持引入网易云音乐,b站视频,插入链接等
- 支持自定义头图,个人头像,网站标题等
- 支持上传图片到S3兼容的云存储,支持本地存储
- 适配手机
- 支持暗黑模式
- 数据库采用sqlite,可随时备份
- 支持引入豆瓣读书/豆瓣电影,样式来源于[这里](https://github.com/TankNee/hexo-douban-card/blob/master/templates/assets/style.css)

有其他需求欢迎提issues.

默认用户名密码:`admin/a123456`,登录进去后后台可以自己修改密码.

## 自定义其他配置

打开[配置管理器](https://mconfig.mblog.club),配置好后点击一键复制配置,然后进入moments后台拉到最底下,导入进去,保存即可生效.


## 使用google recaptchaV3(可选)

自行去[google recaptchaV3 admin console](https://www.google.com/recaptcha/admin/create)开通,每月100万次免费调用.
开通成功后复制网站密钥和通信密钥,填入上方的环境变量对应的key里面.


## Docker启动
Docker首次启动看[这里](https://github.com/kingwrcy/moments/blob/master/docker-start.sh)

Docker更新看[这里](https://github.com/kingwrcy/moments/blob/master/docker-update.sh)

## Docker Compose启动
Docker Compose启动看[这里](https://github.com/kingwrcy/moments/blob/master/docker-compose.yml)

## 源码编译启动

首先设置环境变量:

```
-- sqlite数据库位置
DATABASE_URL="file:/app/data/db.sqlite" 
-- 本地上传的文件目录
UPLOAD_DIR="/app/data/upload"
-- 配置文件目录(可以复制项目根目录的)
CONFIG_FILE=/app/data/config.json
-- 自定义jwt密钥(从0.2版本开始必填,不填无法使用)
NUXT_JWT_KEY=自定义jwt密钥,可以自己随机生成
```

执行命令

```
-- 安装依赖
npm install
-- 脚本迁移
npx prisma migrate dev
-- 执行构建
npm run build
-- 预览
npm run preview
```

## 编辑SQLITE数据库

```
# 容器内部执行
npx prisma studio
```

执行上面的命令会在容器内部暴露一个5555端口,暴露到主机后可以通过 `http://容器IP:5555` 访问数据库,直接修改/删除/新增数据.


## 配置S3(可选)

由于使用了[使用预签名 URL 上传对象](https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/userguide/PresignedUrlUploadObject.html)方案来上传图片到S3,简单来说就是前端直接上传文件到S3,不经过服务端.

不支持这个预签名技术的S3无法上传,据我所知,号称兼容S3的云存储大部分都支持这个特性.比如腾讯云,七牛云,阿里云等.

另外,要求在S3上配置跨域,配置你当前的域名能够访问S3的资源,不配置的话,是无法使用的.

比如我这里使用的是[缤纷云](https://www.bitiful.com/),配置如下:

![缤纷云](https://yoyo.s3.bitiful.net/2024/04/12/6618b41d6b65c.png?fmt=webp)

## 重置密码

目前没有别的办法重置密码,只有修改数据库.见[编辑SQLITE数据库](https://github.com/kingwrcy/moments?tab=readme-ov-file#%E7%BC%96%E8%BE%91sqlite%E6%95%B0%E6%8D%AE%E5%BA%93).

或者任何能正常打开SQLITE数据库的工具都行,数据库见前面的环境变量部分.

打开[bcrypt-generator](https://bcrypt-generator.com/)或者其他类似的bcrypt在线加密的网站,加密你的密码.

复制加密后的密码,编辑数据库,更新User表pwd字段,更新完后记得关掉5555端口的映射,执行`npx prisma studio`命令停止5555端口.

## 打赏

如果你觉得这个项目对你有帮助,可以对我打赏,感谢!

![1713695645770.png](https://yoyo.s3.bitiful.net/2024/04/21/6624eb9a4fd18.png)