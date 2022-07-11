# gomodone

git remote -v 没有输出， 于是 git remote add origin https://github.com/teaCupa/gomodone

git init
git add xx
git commit -m ""

git push origin master   
报错remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.

配置令牌
在 setting-> developer settings->  personal access token -> add new token

git remote set-url origin https://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@github.com/teaCupa/gomodone.git
