# 1. ssh 常规配置
* [官方文档] 本地生成ssh密钥，gitlab、github 配置，以及如何使用 config 按照不同 host 配置 ssh 密钥，[教程地址戳这里。](https://docs.github.com/zh/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
* [如何在Macos下配置ssh管理多个github账号](https://www.jibing57.com/2022/02/07/how-to-manage-multiple-github-account-on-macos/)，按照文档配置成功了，官方文档有点坑。


# 2. typescript match 返回值（数组）说明
* [stack overflow question](https://stackoverflow.com/questions/19947120/why-does-javascript-matches-return-multiple-items)

.match() returns an array.

[0] in the return result is the entire match.

[1] is the first matched group (things in parentheses in the regex)

[2] is the second matched group

and so on...