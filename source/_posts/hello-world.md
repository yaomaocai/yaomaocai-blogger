---

title: 音乐
---
第一次使用hexo + github搭建微博踩到的各种神坑
#### 流程
    1. 搭建 Node.js 环境
    2. 搭建 Git 环境
    3. GitHub 注册和配置
    4. 安装配置 Hexo
    5. 关联 Hexo 与 GitHub Pages
    6. GitHub Pages 地址解析到个人域名  
详细教程百度一大堆 我就说一说遇到的问题吧
hexo官方文档:https://hexo.io/zh-cn/
#### 要点
###### 以上环境都安装完成后本地运行命令
    1.$ hexo server //可以在本地浏览器中查看http://localhost:4000
    2.$ hexo generate//生成静态文件才能发布到github
    3.$ hexo deploy //部署到github仓库
### 细节
###### 1.站点文件_config.yml deploy下一定要注意跟自己的github链接一致
    type: git
    repository: https://github.com/yaomaocai/yaomaocai.github.io.git
    branch: master
###### 2.在github新建仓库的时候一定要注意名称的规范
    如:yourname.github.io