<div align="center">
    <a href="https://github.com/MarSeventh/CloudFlare-ImgBed"><img width="80%" alt="logo" src="static/readme/banner.png"/></a>
    <p><em>🗂️开源文件托管解决方案，支持 Docker 和无服务器部署，支持 Telegram Bot 、 Cloudflare R2 、S3 等多种存储渠道，支持 WebDAV 协议和多种 RESTful API</em></p>
    <p>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/blob/main/README.md">简体中文</a> | <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/blob/main/README_en.md">English</a> | <a href="https://cfbed.sanyue.de">官方网站</a>
    </p>
    <div>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/MarSeventh/CloudFlare-ImgBed" alt="License" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/releases">
        <img src="https://img.shields.io/github/release/MarSeventh/CloudFlare-ImgBed" alt="latest version" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/releases">
        <img src="https://img.shields.io/github/downloads/MarSeventh/CloudFlare-ImgBed/total?color=%239F7AEA&logo=github" alt="Downloads" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/issues">
          <img src="https://img.shields.io/github/issues/MarSeventh/CloudFlare-ImgBed" alt="Issues" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/stargazers">
          <img src="https://img.shields.io/github/stars/MarSeventh/CloudFlare-ImgBed" alt="Stars" />
        </a>
        <a href="https://github.com/MarSeventh/CloudFlare-ImgBed/network/members">
          <img src="https://img.shields.io/github/forks/MarSeventh/CloudFlare-ImgBed" alt="Forks" />
        </a>
    </div>
</div>

<<<<<<< HEAD
=======




>>>>>>> 8b4ebb4fc8f9b507e0fce1655bb8b80dadef58c5
---

> [!IMPORTANT]
>
> **v2.0 版本升级注意事项请查看公告！**



<details>
    <summary>公告</summary>



## 置顶

1. 部署使用出现问题，请先仔细查阅文档、常见问题解答以及已有issues。

2. **注意**：本仓库为[Telegraph-Image](https://github.com/cf-pages/Telegraph-Image)项目的重制版，如果你觉得本项目不错，在支持本项目的同时，也请支持原项目。

## 2025.2.6  V2.0 版本升级注意事项

> v2.0 版已发布，相较于 v1.0 版本进行了大量改动和优化，但 beta 版本可能存在潜在不稳定性，若您追求稳定，可选择暂缓更新。
>
> 由于**构建命令发生了变化**，此次更新需要您**手动进行**，请按照以下步骤进行操作：
>
> - 同步fork的仓库至最新版（若已自动同步可忽略）
>
> - 前往 pages 管理页面，进入`设置`->`构建`，编辑`构建配置`，在`构建命令`处填写`npm install`
>
> - 新版本所有设置项已**迁移至 管理端->系统设置 界面**，原则上无需再通过环境变量的方式进行设置，通过系统设置界面进行的设置将**覆盖掉**环境变量中的设置，但为了保证 **Telegram渠道的图片** 能够与旧版本相兼容，**若您之前设置了 Telegram 渠道相关的环境变量，请将其保留！**
>
> - 确保上述设置完成无误后，前往 pages 管理页面，进入`部署`，对最后一次不成功的部署进行`重试操作`

## 关于切换到 Telegram 渠道的通知


> 由于telegraph图床被滥用，该项目上传渠道已切换至Telegram Channel，请**更新至最新版（更新方式见第3.1章最后一节）**，按照文档中的部署要求**设置`TG_BOT_TOKEN`和`TG_CHAT_ID`**，否则将无法正常使用上传功能。
>
> 此外，目前**KV数据库为必须配置**，如果以前未配置请按照文档说明配置。
>
> 出现问题，请先查看第5节常见问题Q&A部分。

</details>




# 1. Introduction

<<<<<<< HEAD
- **编辑器内自动上传（油猴脚本）**：https://greasyfork.org/zh-CN/scripts/529816-image-uploader-to-markdown-to-cloudflare-imgbed （_作者：Linux.do: [calg_c](https://linux.do/u/calg_c/summary)_）

## 2.仓库

- **向TG BOT发送文件上传图床**：[uki0xc/img-up-bot: 使用telegram机器人链接图床进行上传](https://github.com/uki0xc/img-up-bot?tab=readme-ov-file) （_作者：[uki0xc](https://github.com/uki0xc)_)



</details>

<details>
    <summary>体验地址及优质博文、视频（搭建或使用有问题可以先去里面学习哦~）</summary>


**体验地址**：[CloudFlare ImgBed](https://cfbed.1314883.xyz/)

> 访问码：cfbed

**体验视频**：[CloudFlare免费图床，轻松守护你的每一份精彩！_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1y3WGe4EGh/?vd_source=da5ecbe595e41089cd1bed95932b8bfd)

**相关教程视频**：

- [利用Cloudflare R2 +Pages搭建在线图床系统，不限空间，不被墙，超级简单，完全免费 (youtube.com)](https://www.youtube.com/watch?v=T8VayuUMOzM)

**相关优质博文（感谢每一位鼎力支持的热心大佬）：**

- [CloudFlare-ImgBed项目 – yunsen2025的小窝](https://www.yunsen2025.top/category/cloudflare-imgbed/)
  - [完全免费，图文教程手把手教你使用cloudflare搭建一个无限空间的私人图床 支持身份认证与成人元素鉴定！ - yunsen2025的小窝](https://www.yunsen2025.top/blog-cfpages-syq-imgbed)
  - [为CloudFlare-ImgBed图床配置国内CDN并分线路解析，以最低成本享受极致速度！ – yunsen2025的小窝](https://www.yunsen2025.top/cloudflare-imgbed-fen-xian-pei-zhi-guo-nei-cdn/)
- [利用cloudflare pages搭建telegram频道图床 (lepidus.me)](https://blogstr.lepidus.me/post/1725801323700/)
- [搭建基于CloudFlare和Telegram的免费图床教程 - 刘学馆 | Blog (sexy0769.com)](https://blog.sexy0769.com/skill/735.html)
- [CloudFlare+Github，打造属于自己的免费图床 - 大头钉的小小blog (luckyting.top)](https://luckyting.top/index.php/archives/20/)

</details>



## 最近更新

Add Features:

- **支持通过Docker在服务器上部署**





<details>
    <summary>更新日志</summary>


## 2025.5.11

Add Features:

- 支持通过Docker在服务器上部署

## 2025.3.14

Add Features:

- 上传用户管理支持显示IP具体位置

## 2025.3.8

Add Features:

- 随机图API支持按目录读取，支持按目录进行权限控制

Fix Bugs:

- 修复随机图API的缓存问题

## 2025.3.7

Add Features:

- **目录功能上线啦**，当前支持：
  - 上传到指定目录
  - 整目录删除
  - 文件位置移动（ Telegraph 和旧版 Telegram 渠道不支持移动）
  - 按目录读取文件
- 随机图API支持按目录读取

Fix Bugs:

- 修复多项影响体验的bug

## 2025.3.1

Add Features:

- 支持粘贴多个链接同时上传
- 支持存储和管理外链

Fix Bugs:

- 修复管理端复制 S3 链接的有关问题
- 修复管理端部分页面设置不生效的问题
- 修复渠道设置某些情况下不能保存的问题

## 2025.2.6

**v2.0版本焕新登场**，带来多项新功能和优化，给您焕然一新的用户体验：

💪**更强大**：

- 接入 S3 API 渠道，支持 Cloudflare R2 , Backblaze B2 ，七牛云，又拍云等多个服务商的对象存储服务
- 支持设置多个 Telegram 和 S3 渠道，支持多渠道负载均衡
- 上传文件支持短链接命名方式

✈️**更高效**：

- 全部设置项迁移到管理端系统设置界面，无需进行环境变量的繁琐配置，立即设置立即生效
- 管理端 Gallery 和 用户管理 等页面实现分页读取，提升前端渲染速度，优化使用体验
- 支持禁用、启用渠道，渠道管理自在掌握
- 多个设置项加入提示弹窗，不用到处翻阅文档，设置更踏实

✨**更精致**：

- 全局支持深色模式，根据用户喜好和时间自动切换，凸显满满高级感
- 登陆页面、图库页面、用户管理页面等多个页面细节重新打磨，操作更直观
- 上传页全新 Tab 栏，一拉一合，灵动又便捷
- Logo 焕新，纯手工打造，能力有限，不喜勿喷（
- 支持自定义隐藏页脚，强迫症患者有救啦

## 2024.12.27

Add Features:

- 支持通过环境变量自定义全局默认链接前缀（见3.1.3.6自定义配置接口）
- 管理端支持自定义链接前缀
- 管理端部分页面展示效果优化
- `/upload`API支持返回完整链接（请求时设置`returnFormat`参数，详见API文档）

Fix Bugs:

- 优化上传页面显示效果

## 2024.12.20

Add Features:

- 管理端支持拉黑上传IP（Dashboard->用户管理->允许上传）
- 管理端批量操作支持按照用户选择的顺序进行（[#issue124](https://github.com/MarSeventh/CloudFlare-ImgBed/issues/124)）
- `random`接口优化，减少KV操作次数，增加`content`参数，支持返回指定类型的文件
- 接入CloudFlare Cache API，提升 list 相关接口访问速度
- 正常读取返回图片的CDN缓存时间从1年调整为7天，防止缓存清除不成功的情况下图片长时间内仍可以访问的问题

## 2024.12.14

Add Features:

- 管理端增加批量黑名单、白名单功能

## 2024.12.13

Add Features:

- 优化blockimg、whitelistmode、404等返回状态的缓存策略，尽可能减少回源请求(参考文档`3.1.3.9管理端删除、拉黑等操作优化`进行设置)

## 2024.12.12

Add Features: 

- 后端支持上传失败自动切换其他渠道重试
- 优化404、blockimg、whitelistmode等返回状态的显示样式

## 2024.12.11

Add Features:

- 进行删除、加入白名单、加入黑名单等操作时，自动清除CF CDN缓存，避免延迟生效(参考文档`3.1.3.9管理端删除、拉黑等操作优化`进行设置)

## 2024.12.10

Add Features:

- 文件详情增加文件大小记录

## 2024.12.09

Add Features:

- 开放更多文件格式

Fix Bugs:

- 读取文件响应头增加允许跨域头`access-control-allow-origin: *`

## 2024.12.04

Add Features:

- 支持自定义命名方式（仅原名 or 仅随机前缀 or 默认的随机前缀_原名）
- Telegram Channel渠道上传文件记录机器人和频道数据，便于迁移和备份
- 支持自定义链接前缀

Fix Bugs:

- R2渠道在管理端删除时，存储桶同步删除

## 2024.11.05

Add Features:

- 增加对R2 bucket的支持

## 2024.10.20

Add Features:

- 页脚增加自定义传送门功能

## 2024.09.28

Add Features:

- 上传页面右下角工具栏样式重构，支持上传页自定义压缩（上传前+存储端）
- 增加仅删除上传成功图片、上传失败图片重试

## 2024.09.27

Add Features:

- 上传页面点击链接时，自动复制到剪切板
- 上传设置记忆（上传方式、链接格式等）

Fix Bugs:

- 若未设置密码，无需跳转登录页

## 2024.09.26

Add Features:

- 优化粘贴上传时的文件命名方法

## 2024.09.12

Add Features:

- 增加背景透明度支持自定义

## 2024.09.11

Add Features:

- 支持背景切换时间自定义

## 2024.08.26

Add Features:

- 支持大于5MB的图片上传前自动压缩
- 图床名称和Logo支持自定义
- 网站标题和Icon支持自定义

## 2024.08.23

Add Features:

- 支持URL粘贴上传

## 2024.08.21

Add Features:

- 完善多格式链接展示形式，增加UBB格式链接支持
- 完善登录逻辑，后端增加认证码校验接口

## 2024.07.25

Add Features:

- 增加随机图API

Fix Bugs:

- 修复API上传无法直接展示在后台的问题

## 2024.07.22

Add Features:

- 增加粘贴图片上传功能

## 2024.07.21

Add Features:

- 增加Markdown、HTML等格式链接复制功能
- 上传页面增加管理端入口

</details>

# 1.Introduction

免费文件托管解决方案，具有**上传**、**管理**、**读取**、**删除**等全链路功能，覆盖文件全生命周期，支持**鉴权**、**目录**、**图片审查**、**随机图**等各项特性。
=======
免费文件托管解决方案，具有**上传**、**管理**、**读取**、**删除**等全链路功能，覆盖文件全生命周期，支持**鉴权**、**目录**、**图片审查**、**随机图**等各项特性（详见[功能文档](https://cfbed.sanyue.de/guide/features.html)）。
>>>>>>> 8b4ebb4fc8f9b507e0fce1655bb8b80dadef58c5

![CloudFlare](static/readme/海报.png)

# 2. [Document](https://cfbed.sanyue.de)

提供详细的部署文档、功能文档、开发计划、更新日志、常见问题解答等，帮助您快速上手。

[![更新日志](https://recent-update.cfbed.sanyue.de/cn)](https://cfbed.sanyue.de/guide/update-log.html)

# 3. Demo

**演示站点**：[CloudFlare ImgBed](https://cfbed.1314883.xyz/) 访问密码：`cfbed`

![image-20250313204101984](static/readme/202503132041511.png)

![image-20250313204138886](static/readme/202503132041072.png)

<details>
    <summary>其他页面效果展示</summary>

![image-20250313204308225](static/readme/202503132043466.png)

![image-20250314152355339](static/readme/202503141524797.png)

![status-page](static/readme/status-page.png)

![image-20250313204325002](static/readme/202503132043265.png)

</details>

# 4. Tips

- **前端开源**：参见[MarSeventh/Sanyue-ImgHub](https://github.com/MarSeventh/Sanyue-ImgHub)项目。

<<<<<<< HEAD

1. :white_check_mark: ~~增加粘贴图片上传功能~~（2024.7.22已完成）
2. :white_check_mark:~~增加markdown、html等格式链接复制功能~~（2024.7.21已完成）
3. :white_check_mark:~~上传页面增加管理端入口~~（2024.7.21已完成）
4. :memo:增加用户个性化配置接口
   - ~~登录页面和上传页面背景图自定义~~（2024.8.25已完成）
   - ~~图床名称和Logo自定义~~（2024.8.26已完成）
   - ~~网站标题和Icon自定义~~（2024.8.26已完成）
   - ~~背景切换时间自定义~~（2024.9.11已完成）
   - ~~背景透明度支持自定义~~（2024.9.12已完成）
   - ~~页脚自定义传送门~~（2024.10.20已完成）
   - ~~全局自定义链接前缀~~（2024.12.27已完成）
   - ~~可隐藏页脚~~（2025.2.4已完成）
5. :white_check_mark:~~增加随机图API~~（2024.7.25已完成）
6. :white_check_mark:~~完善多格式链接展示形式，增加ubb格式链接支持~~（2024.8.21已完成）
7. :white_check_mark:~~完善登录逻辑，后端增加认证码校验接口~~（2024.8.21已完成）
8. :white_check_mark:~~支持URL粘贴上传~~（2024.8.23已完成）
9. :white_check_mark:~~支持大于5MB的图片上传前自动压缩~~（2024.8.26已完成）
10. :white_check_mark:~~上传页面右下角工具栏样式重构，支持上传页自定义压缩（上传前+存储端）~~（2024.9.28已完成）
11. :white_check_mark:~~重构管理端，认证+显示效果优化，增加图片详情页~~（2024.12.20已完成）
12. :white_check_mark:~~管理端增加访问量统计，IP记录、IP黑名单、上传IP黑名单等~~（2024.12.20已支持上传ip黑名单，访问记录由于对KV读写消耗太大，暂时搁置）
13. :white_check_mark:~~上传页面点击链接，自动复制到剪切板~~(2024.9.27已完成)
14. :white_check_mark:~~上传设置记忆（上传方式、链接格式等）~~（2024.9.27已完成，**两种上传方式合并**）
15. :white_check_mark:~~若未设置密码，无需跳转进入登录页~~（2024.9.27已完成）
16. :white_check_mark:~~增加仅删除上传成功图片、上传失败图片重试~~（2024.9.28已完成）
17. :white_check_mark:~~优化粘贴上传时文件命名方法~~（2024.9.26已完成）
18. :white_check_mark:~~增加对R2 bucket的支持~~（2024.11.5已完成）
19. :white_check_mark:~~管理端增加批量黑名单、白名单功能~~（2024.12.14已完成）
20. :white_check_mark:~~Telegram Channel渠道上传文件记录机器人和频道数据，便于迁移和备份~~（2024.12.4已完成）
21. :white_check_mark:~~支持自定义命名方式（仅原名 or 仅随机前缀 or 默认的随机前缀\_原名）~~（2024.12.4已完成）
22. :white_check_mark:~~支持上传失败自动切换其他渠道尝试~~（2024.12.12已完成）
23. :white_check_mark:~~后端list接口实现分页功能~~（2024.2.5已完成）
24. :white_check_mark:~~支持自定义链接前缀~~（2024.12.4已完成）
25. :memo:对接alist，或实现webdav（评估中）
26. :white_check_mark:~~文件详情增加文件大小记录~~（2024.12.10已完成）
27. :white_check_mark:~~支持管理员自定义全局默认链接前缀~~（2025.2.1已完成）
28. :white_check_mark:~~开放更多文件格式~~（2024.12.9已完成）
29. :white_check_mark:~~进行删除、加入白名单、加入黑名单等操作时，自动清除CF CDN缓存，避免延迟生效~~（2024.12.11已完成）
30. :white_check_mark:~~管理端批量选择时，记录用户选择的顺序~~（2024.12.20已完成）
31. :memo:上传图片支持自定义上传路径，支持相册功能
    - ~~文件夹删除功能~~（2025.3.6已完成）
    - ~~文件位置移动功能~~（2025.3.7已完成）
    - ~~管理端加载更多数据时鬼打墙问题修复~~（2025.3.6已完成）
    - ~~管理端批量操作适配文件夹~~（2025.3.6已完成）
    - ~~管理端分页逻辑调整~~（2025.3.6已完成）
32. :white_check_mark:~~支持多个 Telegram Bot Token 负载均衡~~（2025.2.4已完成）
33. :white_check_mark:~~管理端提供详细的设置信息和设置方式引导~~（2025.2.5已完成）
34. :white_check_mark:~~Logo焕新、登录页面优化、设置提示项等多项展示效果优化~~（2025.2.2已完成）
35. :white_check_mark:~~接入S3 API渠道~~（2024.2.3已完成）
36. :white_check_mark:~~支持短链接命名方式~~（2025.2.1已完成）
37. :white_check_mark:~~支持深色模式~~（2025.1.11已完成）
38. :hourglass_flowing_sand:支持KV备份恢复功能
39. :white_check_mark:~~页脚可自定义隐藏~~（2025.2.4已完成）
40. :hourglass_flowing_sand:搜索功能增强
41. :white_check_mark:支持粘贴多个链接，支持外链管理
42. :hourglass_flowing_sand:上传文件记录MD5，支持文件硬链接
43. :hourglass_flowing_sand:上传页面增加最近上传展示

</details>

## 5.2Fix Bugs👻

<details>
    <summary>Bug修复列表</summary>


1. :white_check_mark:~~修复API上传无法直接展示在后台的问题~~（2024.7.25已修复）
1. :white_check_mark:~~由于telegra.ph关闭上传，迁移至TG频道上传~~（2024.9.7已修复）
1. :white_check_mark:~~修复未设管理员认证时管理端无限刷新的问题~~（2024.9.9已修复）
1. :white_check_mark:~~修复部分视频无法预览播放的问题~~（经测试，暂定为文件自身存在问题，暂无法修复）
1. :hourglass_flowing_sand:增加新的图片审查渠道
1. :white_check_mark:~~R2渠道在管理端删除时，存储桶同步删除~~（2024.12.4已修复）
1. :white_check_mark:~~读取文件响应头增加允许跨域头`access-control-allow-origin: *`~~（2024.12.9已修复）
1. :white_check_mark:~~上传界面加入访问限制白名单~~（2024.12.11已修复）

</details>

# 6.Q&A

<details>
    <summary>常见问题解答</summary>

## 6.1未设置`ALLOWED_DOMAINS`，但无法跨域访问？

- 请检查你的cloudflare防火墙设置（例如hotlink保护是否开启）
- 参见[Issue #8](https://github.com/MarSeventh/CloudFlare-ImgBed/issues/8)

## 6.2如何通过PicGo上传？

- PicGo插件设置中搜索`web-uploader`，安装可自定义前缀的版本，如图：

  ![](static/readme/202408231141491.png)

- 打开`图床设置`->`自定义Web图床`->`Default`，然后按照下图方式配置，注意API地址和自定义图片URL前缀按照自己的域名进行修改。（**如果设置了`AUTH_CODE`，一定以`?authCode=your_authCode`的方式添加到API地址后面**）：

  ![](static/readme/202408261959174.png)

- 设置完成，确定即可使用PicGo上传到自建的图床。

## 6.3上传失败怎么办？

- 是否正确配置`TG_BOT_TOKEN`、`TG_CHAT_ID`等环境变量
- 是否给机器人管理员配置**足够的权限**
- 是否**正确绑定KV数据库**
- 是否更新至**最新版**
- 前往issues寻找相似问题

## 6.4`TG_CHAT_ID`前面有没有`-`

- 注意看图，前面有`-`

## 6.5进入后台页面加载不出记录或图片

- 网络问题，尝试刷新页面

## 6.6后台进行删除、拉黑等操作时不能立即生效

- 与CDN缓存有关
- 详见[[重要\]关于CDN缓存的说明（删除、拉黑等操作延迟生效解决方案） · Issue #123 · MarSeventh/CloudFlare-ImgBed (github.com)](https://github.com/MarSeventh/CloudFlare-ImgBed/issues/123)

</details>

# 7.Tips

- 前端开源，参见[MarSeventh/Sanyue-ImgHub](https://github.com/MarSeventh/Sanyue-ImgHub)项目。
=======
- **生态建设**：欢迎社区参与生态建设，欢迎提交 PR 或者 Issue，优质内容参见[官网生态建设页面](https://cfbed.sanyue.de/about/ecosystem.html)。
>>>>>>> 8b4ebb4fc8f9b507e0fce1655bb8b80dadef58c5

- **赞助**：项目维护不易，喜欢本项目的话，可以作者大大一点小小的鼓励哦，您的每一份支持都是我前进的动力\~ 

  <a href="https://afdian.com/a/marseventh"><img width="200" src="https://pic1.afdiancdn.com/static/img/welcome/button-sponsorme.png" alt=""></a>
  
- **Sponsors**：感谢以下赞助者对本项目的支持！

<<<<<<< HEAD
  <a href="https://afdian.com/a/nothin">
        <img src="https://pic1.afdiancdn.com/user/e8af1436138e11ed945852540025c377/avatar/59db0533d82e4198f59e63df63a1917f_w640_h640_s114.jpeg?imageView2/1/w/240/h/240" width="100"/>
      </a> <a href="https://afdian.com/u/1acef0be02d911ee90695254001e7c00">
        <img src="https://pic1.afdiancdn.com/default/avatar/avatar-orange.png?imageView2/1/w/240/h/240" width="100"/></a><a href="https://afdian.com/u/412189a0284911eca59f52540025c377">
        <img src="https://pic1.afdiancdn.com/default/avatar/avatar-orange.png?imageView2/1/w/120/h/120" width="100"/></a><a href="https://afdian.com/u/5e52ece217bc11f0ae3352540025c377">
        <img src="https://pic1.afdiancdn.com/default/avatar/avatar-purple.png?imageView2/1/" width="100"/></a><a href="https://afdian.com/u/42e1c47e16a411f0baff52540025c377">
        <img src="https://pic1.afdiancdn.com/default/avatar/avatar-purple.png?imageView2/1/" width="100"/></a><a href="https://afdian.com/a/yono233">
        <img src="https://pic1.afdiancdn.com/user/73b45190c98711eeaa425254001e7c00/avatar/26afa95554d4bbcd748e6432ab56f824_w580_h580_s145.jpeg?imageView2/1/w/240/h/240" width="100"/></a>
=======
  [![赞助者](https://afdian-sponsors.sanyue.de/image)](https://afdian.com/a/marseventh)
  
- **Contributors**：感谢以下贡献者对本项目的无私贡献！
>>>>>>> 8b4ebb4fc8f9b507e0fce1655bb8b80dadef58c5

  [![Contributors](https://contrib.rocks/image?repo=Marseventh/Cloudflare-ImgBed)](https://github.com/MarSeventh/CloudFlare-ImgBed/graphs/contributors)

# 5. Star History

**如果觉得项目不错希望您能给个免费的star✨✨✨，非常感谢！**
<<<<<<< HEAD
=======

[![Star History Chart](https://api.star-history.com/svg?repos=MarSeventh/CloudFlare-ImgBed,MarSeventh/Sanyue-ImgHub&type=Date)](https://star-history.com/#MarSeventh/CloudFlare-ImgBed&MarSeventh/Sanyue-ImgHub&Date)

# 6. Special Sponsors

- **[CloudFlare](https://www.cloudflare.com) & [EdgeOne](https://edgeone.ai/?from=github)**：提供CDN加速和安全保护服务

  <a href="https://www.cloudflare.com"><img src="static/readme/cloudflare-logo.png" alt="Cloudflare Logo" height="25"></a> <a href="https://edgeone.ai/?from=github"><img src="https://edgeone.ai/media/34fe3a45-492d-4ea4-ae5d-ea1087ca7b4b.png" alt="Tencent Logo" height="25"></a>

- **[亚洲云](https://www.asiayun.com/aff/WUDVIIUD)**：提供云计算服务资源支持

>>>>>>> 8b4ebb4fc8f9b507e0fce1655bb8b80dadef58c5
