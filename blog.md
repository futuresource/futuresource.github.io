---
title: "Github博客"
date: 2019-07-30T22:10:45+08:00
draft: true
---

futuresource.github.io

# 本地启动hugo服务
```
hugo server -t m10c --buildDrafts
```

# 新建文章
```
hugo new xxx.md
```

# 推送到Github
```
hugo --theme=m10c --baseUrl="https://futuresource.github.io/" --buildDrafts
cd public
git add .
git commit -m "2"
git remote add origin https://github.com/futuresource/futuresource.github.io.git
git push -u origin master
```


