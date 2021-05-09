# sctl


Buy me a cup of coffee for $3

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/M4M54KKIF)

sctl 是一个管理systemd启动脚本的工具，方便你管理自定义的服务。

借助于systemd强大的启动管理能力，再加上一点点小小的修改，sctl帮助你快速创建启动服务。

```

ln -s $(pwd)/sctl /usr/bin/sctl
sctl enable hello
sctl status hello
sctl logs hello
```
