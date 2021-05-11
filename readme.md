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



## License

```
    Copyright (C) 2000-2021 cnmade

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as published
    by the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
