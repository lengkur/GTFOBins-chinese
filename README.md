# GTFOBins

[![CI status](https://github.com/GTFOBins/GTFOBins.github.io/actions/workflows/ci.yml/badge.svg)](https://github.com/GTFOBins/GTFOBins.github.io/actions?query=workflow:CI)
[![CI status](https://github.com/GTFOBins/GTFOBins.github.io/actions/workflows/pages.yml/badge.svg)](https://github.com/GTFOBins/GTFOBins.github.io/actions?query=workflow:Pages)
[![Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&color=%23db61a2)](https://github.com/sponsors/GTFOBins)

<a href="https://gtfobins.org"><img align="right" src="assets/logo.png" style="width: 100px" /></a>

GTFOBins 是一个精心整理的类 Unix 可执行文件列表，可用于绕过配置错误的系统中的本地安全限制。

访问以下网址了解该项目：[gtfobins.org](https://gtfobins.org)



#### 搭建本地服务

```bash
docker build --no-cache ./ -t gtfobins
make 
```

默认端口4000

访问http://127.0.0.1:4000
