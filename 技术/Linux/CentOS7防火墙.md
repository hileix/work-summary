# CentOS7 防火墙

## 开放需要的端口

```shell
sudo firewall-cmd --zone=public --add-port=3000/tcp --permanent
sudo firewall-cmd --reload

# 查看开放的端口
firewall-cmd --list-all
```

## 注意

在 CentOS7 中，发现使用 systemctl disable firewalld 无效，只有使用 `firewall-cmd` 开启端口，才有效。

## 参考

- https://www.jianshu.com/p/bad33004bb4f
