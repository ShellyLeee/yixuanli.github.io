# Jekyll 项目运行指南

最推荐的方式：所有改动都在本地完成 → commit → push，这样本地和线上永远同步。

参考网站：https://www.taniarascia.com/make-a-static-website-with-jekyll/

本地修改：nano YYYY-MM-DD-Name.md, 编辑, ctrl O, backup, ctrl X

本地预览：`bundle exec jekyll serve`

网站：http://localhost:4000/

推到github：
```
git add .
git commit -m "Add new post"
git push
```

Github上修改后本地同步：
```
git pull
```
