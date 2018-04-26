# 我家大美女和狗狗的照骗

### gh-pages
> https://www.cnblogs.com/MuYunyun/p/6082359.html

展示某个目录
```
git subtree push --prefix=dist origin gh-pages
```


整个项目展示
```
git symbolic-ref HEAD refs/heads/gh-pages
git add -A
git commit -m "..."
git push origin gh-pages
```