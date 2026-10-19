# Wenbin Wang 的学术主页

网址：https://kingdomweb618.github.io/ （英文）；https://kingdomweb618.github.io/zh/ （中文）。

## 更新内容

在 GitHub 打开对应文件，点击铅笔编辑，修改后点击 Commit changes。页面自动重新构建；在 Actions 中查看结果。

| 内容 | 文件 |
| --- | --- |
| 中文简介、研究方向、教育、荣誉 | `_data/home/zh.yml` |
| 英文简介、研究方向、教育、荣誉 | `_data/home/en.yml` |
| 两种语言共用的论文列表 | `_data/home/common.yml` |
| 姓名、邮箱、头像文件名、GitHub 账号 | `_config.yml` |
| 头像文件 | `images/wenbin-reading-avatar.png` |
| 配色与银色书法背景的位置、尺寸 | `assets/css/profile-theme.css` |

这三个数据文件采用 JSON 格式，也是有效的 YAML。请保留英文双引号、逗号和方括号；中文和英文需分别修改。
新增荣誉时，在 honors.items 中复制一条记录，修改 text 和 year；相邻记录之间用英文逗号隔开。
上传新头像时使用原文件名即可。修改头像后若显示旧照片，请强制刷新页面。
新增论文时复制 common.yml 中的一整条记录，更换 id、title、authors、venue、year、summary 等字段。

## 发布配置

Settings → Pages：Source 为 Deploy from a branch，Branch 为 main，Folder 为 / (root)。Custom domain 留空。
本项目使用 Jekyll，不要添加 .nojekyll，也不要只上传预览 index.html。

## 来源与许可

Built with Jekyll and AcademicPages / Minimal Mistakes.
Template source: https://github.com/T-S-Liang/t-s-liang.github.io
Retain the repository's original LICENSE and third-party license notices.
