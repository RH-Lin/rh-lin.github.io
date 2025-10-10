# Ronghao Lin's Personal Website

Powered by Jekyll's static HTML, along with Bootstrap's CSS style. 

Copyright: Ronghao Lin.


<!-- git remote add origin https://github.com/RH-Lin/rh-lin.github.io
git branch -m master main
git add .
git commit -m "Update"
git push origin main -->

<!-- Thanks to the following reference!!! -->

<!-- https://github.com/RayeRen/acad-homepage.github.io -->
<!-- https://github.com/scofield7419/scofield7419.github.io -->

<!-- 1. 配置谷歌学术引用爬虫：
    1. 在你的谷歌学术引用页面的url里找到你的谷歌学术ID：例如，在url https://scholar.google.com/citations?user=SCHOLAR_ID 中，`SCHOLAR_ID`部分即为你的谷歌学术ID。
    1. 在github本仓库页面的`Settings -> Secrets -> Actions -> New repository secret`中，添加`GOOGLE_SCHOLAR_ID`变量：`name=GOOGLE_SCHOLAR_ID`、`value=SCHOLAR_ID`。
    1. 在github本仓库页面的`Settings -> Actions -> General -> Workflow permissions`设置为`Read and write permissions`。
    本action将会谷歌学术引用的统计量数据`gs_data.json`到本仓库的`google-scholar-stats`分支中。每次修改main分支的内容会触发该action。本action也会在每天08:00 UTC定时触发。
1. 使用 [favicon-generator](https://redketchup.io/favicon-generator)生成favicon（网页icon文件），并下载所有文件到`REPO/images`。
1. 修改主页配置文件[_config.yml](_config.yml) -->