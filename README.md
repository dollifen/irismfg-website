# IRIS Manufacturing Ltd. - Website

## File Structure

```
irismfg-website/
├── index.html              ← 主页 (v1版本)
├── about.html              ← 公司介绍
├── products.html           ← 产品展示
├── certificates.html       ← 证书展示
├── contact.html            ← 联系我们
├── robots.txt              ← AI爬虫允许规则 (上传到网站根目录)
├── llms.txt                ← AI快速了解公司的入口 (上传到网站根目录)
├── schema.html             ← Schema结构化数据代码参考
├── sitemap.xml             ← 网站地图 (上传到网站根目录)
├── css/
│   └── style.css           ← 样式表
├── images/                 ← 图片目录 (需要添加产品图片)
└── v2/
    └── index.html          ← 备用版本 (深色主题, 单页滚动)
```

## GEO/AEO 优化清单

### 已完成
- [x] robots.txt - 允许所有AI爬虫 (GPTBot, ClaudeBot, PerplexityBot等)
- [x] llms.txt - AI快速了解公司的结构化文本
- [x] Schema.org Organization - 公司结构化数据
- [x] Schema.org FAQPage - FAQ结构化数据 (7个常见问题)
- [x] Schema.org BreadcrumbList - 面包屑导航
- [x] Open Graph 标签 - 社交分享优化
- [x] 语义化HTML5 - header, nav, main, section, footer
- [x] 响应式设计 - 移动端适配
- [x] FAQ内容 - 问答式内容, AI容易提取
- [x] 联系信息完整 - 电话/邮箱/地址/微信

### 需要你手动完成
- [ ] 上传 robots.txt 到网站根目录
- [ ] 上传 llms.txt 到网站根目录
- [ ] 上传 sitemap.xml 到网站根目录
- [ ] 将 schema.html 中的script标签复制到每个页面的<head>中
- [ ] 添加产品实拍图片替换CSS渐变占位符
- [ ] 注册 Google Business Profile
- [ ] 创建 LinkedIn Company Page
- [ ] 注册 Alibaba.com 店铺
- [ ] 注册 Made-in-China.com
- [ ] 邀请客户在Google上留评价

## 部署说明

### 方案A: 替换凡科网站
1. 将所有HTML文件上传到凡科后台文件管理
2. 联系凡科客服设置首页为index.html
3. 上传robots.txt和llms.txt到根目录

### 方案B: 独立部署 (推荐)
1. 购买域名和服务器 (推荐: 阿里云/腾讯云)
2. 将所有文件上传到服务器
3. 配置SSL证书 (HTTPS)
4. 提交sitemap.xml到Google Search Console
5. 提交到Bing Webmaster Tools

### 方案C: GitHub Pages (免费)
1. 创建GitHub仓库
2. 上传所有文件
3. 启用GitHub Pages
4. 绑定自定义域名

## 联系信息

- **Jacky Xu** (Founder & CEO): jacky@irismfg.com
- **Dollifen Zhang** (Customer Service): dollifen@irismfg.com
- **Iris Cheung** (OEM Manager): iris@irismfg.com
- **Tel**: +86-791-83415488
- **Mobile**: +86-18174049557
- **WeChat**: dollifen
