# YouBBS for VPS v2.01

#### 感谢 eoen 作了v2.0 的工作。让youBBS 更好看，代码更整齐，也让我有点动力更新youBBS。

## youBBS V2.01 的一点改变

* 修改模版上的一些链接bug
* 页面脚本小的改动
* 添加tag 及相关帖子
* 使用file-cache 缓存，让youBBS 更飞快

------

#### 鉴于YouBBS益于开源，归于开源的分享精神，现在公布v2.0（VPS）版本的源码。

##### YouBBS 是一款轻量级的论坛程序，基于标准的php+mysql环境;为了让url更优美，服务器必须支持rewrite。

#### demo示例 [V2demo](http://www.skodacn.com/)
####
<p>youBBS是开源项目，可自由修改，但要保留Powered by YouBBS链接信息</p>

详细安装说明:
* 修改config.php 配置数据库信息
* 导入数据 youbbs_mysql.sql
* youbbs_nginx.conf nginx 配置参考

<p>这个版本在原版的基础上做了一些很大的功能上的新增与改进，所以在安装这个版本之前最好删除之前的代码在重新部署！（注意备份数据）</p>

## 改进的部分：
* 404页面；
* 网址链接；
* 网页字体；
* 帖子内链接格式化；
* 电脑和手机前端模版样式；
* 发表在第一分类的帖子不会在首页显示；
* 把上传的文件统一到/upload/files/文件夹；
* 把用户信息、发新帖、信息提示固定到右侧；

## 新增的部分：
* 输入帮助信息；
* 返回顶部按钮；
* 登陆页svg动画；
* 简体转繁体功能；
* Font-Awesome UI；
* 谷歌二次验证功能；
* 头部底部动态背景；
* 首页置顶和分类置顶功能；
* 首页推荐和分类推荐功能；

## 删除的部分：
* 搜索功能；
* 沉迂代码；

 P.S: 不支持IE9版本以下的浏览器！ 

## 感谢：
[@sharking](http://www.shacas.com/) 为此版本开发的Google Authenticator二次验证功能!
