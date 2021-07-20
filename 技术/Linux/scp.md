# scp 命令

用于 linux 之间复制文件和目录。

## 将本地文件复制到远程服务器

```shell
# 将 /Users/apple/Desktop/test.js 文件复制到 ip 为 10.1.2.3 的服务器的 /root 目录下
# 且以 root 用户登录，运行命令需要输入 root 用户的密码
scp /Users/apple/Desktop/test.js root@10.1.2.3:/root
```

## 参考

- https://www.runoob.com/linux/linux-comm-scp.html
