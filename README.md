# PbootCMS

### PbootCMS是全新内核且永久开源免费的PHP企业网站开发建设管理系统，是一套高效、简洁、 强悍的可免费商用的PHP CMS源码，能够满足各类企业网站开发建设的需要。系统采用简单到想哭的模板标签，只要懂HTML就可快速开发企业网站。官方提供了大量网站模板免费下载和使用，将致力于为广大开发者和企业提供最佳的网站开发建设解决方案。
* 系统采用高效、简洁、强悍的模板标签，只要懂HTML就可快速开发企业网站；
* 系统采用PHP语言开发，使用自主研发的高速多层开发框架及缓存技术；
* 系统默认采用sqlite轻型数据库，放入PHP空间即可直接使用，可选mysql等数据库，满足各类存储需求；
* 系统采用响应式管理后台，满足各类设备随时管理的需要；
* 系统支持后台在线升级，满足系统及时升级更新的需要；
* 系统支持内容模型、多语言、自定义表单、筛选、多条件搜索、小程序、APP等功能；
* 系统支持多种URL模式及模型、栏目、内容自定义地址名称，满足各类网站推广优化的需要。

##  简单到想哭的模板标签：
```
1、全局标签示意：
{pboot:sitetitle} 站点标题 
{pboot:sitelogo} 站点logo

2、列表页标签示意：
{pboot:list num=10 order=date}
	<p><a href="[list:link]">[list:title]</a></p>
{/pboot:list}

3、内容页标签示意：
{content:title} 标题
{content:subtitle}副标题
{content:author} 作者
{content:source} 来源

更多简单到想哭的标签请参考开发手册...

```

##  修改：
* 移除Kernel.php的加密
* 移除域名授权

##  版权：
Forked From https://github.com/hnaoyun/PbootCMS

