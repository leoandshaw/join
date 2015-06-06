## 中国·支教联盟(CNAEF) [报名系统](http://www.go9999.com)

### 项目说明

这个项目为联盟的报名网站，主要提供志愿者信息提交、审核的功能。

支教不一定非要身体力行的远赴千里之外，考虑现实状况，我们远赴千里之外往往会成为『支教过程中的负担』，如果你愿意为山区的孩子们做点什么，可以考虑做下面的事情：

- 帮助组织Review代码，发起PR，改进或者修复代码。
- 帮助组织开发新的功能。
- 捐赠你不需要，但是孩纸们能用的到的书本、衣物。
- 赞助服务器以及CDN资源或者费用。
- 帮着进行社区宣传社区宣传，偶尔的转发微博、微信、Q群，etc...

### 需求文档

- 一个简单可维护的网站。
- 报名表单高可用。

### 特别注意

- 报名的志愿者会在各种渠道看到宣传信息，手机报名者很多，所以需要兼容移动端展示，并考虑特别古老的手机。
- 报名的志愿者使用的PC端浏览器需要兼容8-，样式可部分牺牲，功能保证可用。

### 目录结构

```
├── LICENSE
├── README.md
├── conf                    服务器软件配置目录
├── docs                    项目相关文档目录
├── logs                    项目日志目录
└── public                  项目目录
    ├── aef-404.php             默认404页面
    ├── aef-config.php          配置文件
    ├── aef-content             资源目录
    │   └── theme               模板目录
    ├── aef-include             程序目录
    ├── aef-load.php            加载器
    ├── error-forbidden.php     禁止访问提示页面
    ├── favicon.ico
    ├── images              外链的图片目录
    │   └── logo.gif            本站友链Logo文件
    ├── index.php           程序入口文件
    └── main.php            后台入口文件
```


### 组织简介

    中国•支教联盟(CNAEF)，创办于2006年4月。由自愿支持农村中小学教育的社会各界爱心人士自发组织的全国性民间公益机构。
    以联系和提供支教为主题，主要发布支教信息，传播贫困地区教育现状，共同关注孩子成长。
    自成立以来，长期致力于为发达地区爱心咨询寻找资助对象，为欠发达地区教育引入社会各界力量。
