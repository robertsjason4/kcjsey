八方娱乐登录【Q-——333307——】八方娱乐登录【 辋芷《888yx●vip》 】
八方娱乐登录【Q-——333307——】八方娱乐登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

你是不是也在纠结——想写技术博客，但服务器要花钱，域名备案麻烦，平台又限制太多？其实，用 GitHub Pages + Hexo 就能免费搭建一个完全属于自己的博客网站。这篇文章手把手教你完成全流程，建议先点赞收藏，方便实操时对照查看。

 为什么选择 GitHub Pages + Hexo？

- 完全免费：托管在 GitHub 服务器上，无需购买主机
- 高度自定义：主题、布局、插件全由你掌控
- SEO友好：静态页面加载快，天然适合搜索引擎收录（比如百度收录）
- 版本管理：所有文章都是 Git 仓库中的 Markdown 文件，历史记录清晰

 搭建前的准备

你需要准备：
1. 一个 GitHub 账号（没有的话先去注册）
2. Node.js 环境（建议 v18 及以上版本）
3. Git 并配置好 SSH Key

 五步搭建完整博客

 第一步：安装 Hexo 脚手架

打开终端，全局安装 Hexo：

```bash
npm install -g hexo-cli
```

 第二步：初始化博客项目

在本地创建博客文件夹并安装依赖：

```bash
hexo init my-blog
cd my-blog
npm install
```

 第三步：配置站点信息

编辑 `_config.yml` 文件，修改标题、作者、关键词等核心信息。建议在关键词中布局"GitHub博客教程"、"Hexo搭建指南"等搜索热词，有助于百度收录。

 第四步：关联 GitHub 仓库

在 GitHub 上新建仓库，命名为 `你的用户名.github.io`，然后安装部署插件：

```bash
npm install hexo-deployer-git --save
```

编辑 `_config.yml`，将 deploy 配置指向你的仓库地址。

 第五步：写文章并发布

新建文章（在 `source/_posts` 目录下），然后一键部署上线：

```bash
hexo new "我的第一篇博客"
hexo clean && hexo generate && hexo deploy
```

几分钟后，访问 `你的用户名.github.io` 就能看到博客了。

 提升百度收录的三个关键动作

1. 主动提交 sitemap：安装 `hexo-generator-sitemap`，并将生成的 `sitemap.xml` 提交到百度站长平台
2. 善用外链：在知乎、掘金等平台分享你的博客链接，加速爬虫抓取
3. 持续更新：百度对内容质量要求高，稳定更新比一次性发布几十篇更有效

 遇到问题怎么办？

最常见的问题是部署后页面空白，大多是 `_config.yml` 中的 `url` 未修改成你的 GitHub Pages 地址，检查后重新部署即可。

---

你现在开始动手搭建了吗？ 如果在第2步或第4步遇到具体报错，可以直接在评论区留言截图，我看到后会第一时间帮你排查。也可以关注我，后续会更新"如何自定义主题"和"绑定免费域名"的进阶教程。

相关推荐：

https://github.com/morenospencer5864/qyacij/blob/main/C%E1%BB%91c%20Games%20%F0%9F%A5%8A%EF%BC%9A%E5%85%AB%E6%96%B9%E4%B8%BB%E7%AE%A1app_%E9%80%80%E5%B1%8E%E8%A1%B7%E7%9F%AD%E6%B7%A4ymupk.md

<img src="https://i.postimg.cc/SNJVQzyQ/bafang-00008.png" />

相关推荐：

https://github.com/morenospencer5864/qyacij/commit/ea495765dd7933a7ec2f1b3831627a984ae8e378

<img src="https://i.postimg.cc/JzXqZVD9/bafang-00015.png" />
相关推荐：

https://github.com/powellcharles077/btiqzm/blob/main/Tr%E1%BB%B1c%20tuy%E1%BA%BFn%20%F0%9F%90%93%EF%BC%9A%E5%85%AB%E6%96%B9_%E6%9C%94%E8%A8%80%E8%B0%AD%E5%92%BD%E8%B0%84lkeee.md

<img src="https://i.postimg.cc/JzXqZVD9/bafang-00015.png" />
相关推荐：

https://github.com/powellcharles077/btiqzm/commit/9f6ebe9254e6562b426a735651732d355d97719b

<img src="https://i.postimg.cc/kMjfdyd3/bafang-00005.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
