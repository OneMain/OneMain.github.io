# OneMain.github.io
cherry的美站

Hexo是一个快速、简洁且高效的博客框架，而Github是一个免费的代码托管工具，利用Github Page可以免费创建一个静态网站。下面将介绍如何使用Hexo和Github，在win10环境下搭建一个静态的博客。

### 安装和配置Hexo及Github
### 安装Hexo

安装Hexo前，需要安装以下：

Node.js
Git
如果已经安装完成以上程序，打开Git-bash或者cmd，输入

npm install -g hexo-cli
即可完成Hexo的安装。

使用Hexo进行本地建站,hexo并不是全局安装
创建一个文件夹，比如 mkdir blog

输入

cd D:\hexo
hexo init
npm install
如果hexo安装成功，则在D:\hexo文件夹下的文件目录为
<pre><code>
.
├── _config.yml // 网站的配置信息，你可以在此配置大部分的参数。
├── package.json 
├── scaffolds // 模板文件夹。当你新建文章时，Hexo会根据scaffold来建立文件。
├── source // 存放用户资源的地方
|   ├── _drafts
|   └── _posts
└── themes // 存放网站的主题。Hexo会根据主题来生成静态页面。
</code></pre>
详细文件或文件夹的具体含义见 Hexo官方文档之建站

为了测试本地建站是否成功，输入

hexo s
<p>主题变化，可以在网上自行下载，提供一个不错的模板链接</p>
</p>https://github.com/yelog/hexo-theme-3-hexo</p>
下载后将文件放在themes/
同时记得修改自己项目的_config.yml
themes: 下载的模板文件夹名称
