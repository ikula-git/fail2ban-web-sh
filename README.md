# 基于fail2ban安全搭建web的脚本
## 用法

```bash
curl -sS -O https://raw.githubusercontent.com/ikula-git/fail2ban-web-sh/main/iku.sh && chmod +x iku.sh && ./iku.sh
```

## 支持的Linux系统

```shell
Ubuntu Debian CentOS Alpine
```

> [!WARNING]
>
> 当前版本未配置GitHub加速，国内机器可能无法使用，建议使用国外机器进行部署
>
> cloudflare的SSL/TLS加密需要设置为完全（严格），否则会出现站点重定向次数过多而无法访问

[SSL/TLS]: https://github.com/ikula-git/fail2ban-web-sh/blob/main/picture/SSL_TLS.jpg?raw=true

