# DAMP Alternative

Docker + Apache + MySQL + PHP. Very Moist!

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu) [![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

This is almost as same as [DAMP](https://github.com/catscarlet/damp), but more focus on replacing existing LAMP supported services.

DAMP Project is licensed under the GLWT and the Anti 996 License Version 1.0 (Draft)
**Make sure you know Docker and Apache well, and backup all your serivces and data before trying this project.**

## Changed

This project has these changes between [DAMP](https://github.com/catscarlet/damp)

- use **host mode as** network_mode instead of bridge mode.
- use `/var/www/html` instead of standalone directory
- use shared website configurations instead of standalone configurations

## Usage

**network_mode: host** means ports(80, 443, 3306, 9000) of Apache, PHP and MySQL are listened on host, as same as LAMP. Using `/var/www/html` means you don't need to remove old file, so does configurations.

For more information, refer to original document of [DAMP](https://github.com/catscarlet/damp).
