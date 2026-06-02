---
layout: page
title: GTFOBins
description: GTFOBins 是一个经过整理的 Unix-like 可执行文件清单，用于记录在配置不当的系统中可被用来绕过本地安全限制的合法功能。
---

![GTFOBins logo]({{ '/assets/logo.png' | relative_url }}){:.logo}

{{ page.description }}

本项目[收集]({{ '/scope/' | relative_url }}) Unix-like 可执行文件的合法功能。这些功能在特定条件下可能被用于逃逸受限 shell、提升或维持权限、传输文件、生成绑定 shell 和反弹 shell，以及完成其他后渗透任务。

GTFOBins 由 [Emilio Pinna][norbemi]、[Andrea Cardaci][cyrus_and] 以及许多其他[贡献者][contributors]共同维护。任何人都可以通过补充条目和技术来[参与贡献]({{ '/contributing/' | relative_url }})。

如果你需要 Windows 二进制文件相关内容，请访问 [LOLBAS][]。

> 请注意，这里**不是漏洞利用列表**。列出的程序本身并不一定存在漏洞；GTFOBins 记录的是在只能使用特定可执行文件时，如何利用系统自带工具完成相关操作。

[GitHub][]
|
[参与贡献]({{ '/contributing/' | relative_url }})
|
[贡献者][contributors]
|
[JSON API]({{ '/api.json' | relative_url }})
|
[MITRE ATT&CK® Navigator](https://mitre-attack.github.io/attack-navigator/#layerURL={{ '/mitre.json' | absolute_url }})
{:.centered}

[contributors]: https://github.com/GTFOBins/GTFOBins.github.io/graphs/contributors
[norbemi]: https://x.com/norbemi
[cyrus_and]: https://x.com/cyrus_and
[LOLBAS]: https://lolbas-project.github.io/
[GitHub]: https://github.com/GTFOBins/GTFOBins.github.io

<div>{%- include gtfobins_table.html -%}</div>
