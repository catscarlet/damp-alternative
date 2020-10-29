# DAMP Alternative

Docker + Apache + MySQL + PHP，特别潮的解决方案。

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu) [![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

此项目与项目 [DAMP](https://github.com/catscarlet/damp) 几乎相同，但是更着重于更新替换已有的 LAMP 服务器环境。

DAMP 项目使用 GLWTPL 和 Anti 996 License Version 1.0 (Draft) 授权

**尝试此项目之前，请确保您对 Docker 和 Apache 有一定的了解，并完全备份你的服务器环境和文件**

## 变更

与 [DAMP](https://github.com/catscarlet/damp) 项目相比，本项目拥有以下变更：

- Docker 网络模式(network_mode) 使用 主机模式(host) 而非 桥接模式(bridge)
- 网站目录使用 `/var/www/html` 而非独立目录
- 网站配置文件使用共享结构而非独立结构

## 使用

网络模式(network_mode)使用主机模式(host)意味着 Apache、PHP 和 MySQL 将直接在主机端口监听，与 LAMP 相同。网站目录使用 `/var/www/html` 意味着你不需要移动现有文件。配置文件的结构相同。

更多信息请参考 [DAMP](https://github.com/catscarlet/damp).
