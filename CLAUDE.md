# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a documentation and knowledge base repository focused on Android reverse engineering, security research, and ticketing platform analysis. It contains educational materials, tutorials, and reference resources primarily in Chinese.

## Content Structure

### Jupyter Notebooks (Root Directory)

The main educational content is organized as `.ipynb` notebooks:

**Android Reverse Engineering:**
- `Android逆向之旅—Frida Hook教程.ipynb` - Frida hooking tutorials
- `Android逆向之旅—Frida普适代码合集.ipynb` - Frida universal code collection
- `Android逆向之旅—Frida检测与反检测.ipynb` - Frida detection and bypass
- `Android逆向之旅—Root检测与反检测.ipynb` - Root detection and bypass
- `Android逆向之旅—抓包：过证书验证.ipynb` - Packet capture: certificate pinning bypass
- `Android逆向之旅—脱壳：Frida脱壳实战.ipynb` - Unpacking with Frida
- `Android逆向之旅—r0env逆向环境解读.ipynb` - r0env reverse engineering environment
- `Android逆向之旅—工具-GDA*.ipynb` - GDA analysis tool usage

**Python:**
- `Python 加密 - 代码实现.ipynb` - Cryptography implementation
- `Python 加密之Crypto、pycrypto、pycryptodome.ipynb` - Crypto libraries comparison
- `Python 加密之base64库详解.ipynb` - Base64 encoding details
- `Python 并发编程之*.ipynb` - Concurrency programming (processes, threads)

**JavaScript:**
- `JavaScript—CryptoJS加解密.ipynb` - CryptoJS encryption/decryption
- `Js逆向之旅—Js反爬技术与处理手段汇总.ipynb` - JS anti-scraping techniques

**Tools:**
- `工具—Unidbg.ipynb` - Unidbg usage
- `工具—Wireshark详解.ipynb` - Wireshark analysis
- `工具—Apktools安装使用.ipynb` - APKTool installation and usage
- `Linux—Tmux 会话管理工具的使用.ipynb` - Tmux usage

### Directories

- `adb相关/` - ADB tools and drivers
- `抓包工具/` - Packet capture tools (frida-server, HttpCanary certificates, Wireshark manual)
- `隐藏root/` - Root hiding tools (Magisk, Shamiko, SafetyNet bypass)
- `其他工具/` - Miscellaneous tools (MT Manager, tcpdump)
- `大麦源码/` - Damai source code (placeholder)

### Reference Files

- `工具与常用网址集.md` - Curated list of tools and documentation links (Frida docs, Android source mirrors, etc.)
- `fastboot常用命令.txt` - Fastboot command reference
- `fastboot刷底层分区镜像列表.txt` - Fastboot partition flashing reference

## Key API Domains (from README.md)

Ticketing platform API endpoints documented for research purposes:
- 大麦 (Damai): `mtop.damai.cn/h5/mtop.alibaba.damai.*`
- 猫眼 (Maoyan): `yanchu.maoyan.com/myshow/ajax/`, `wx.maoyan.com/maoyansh/myshow/`
- 票星球: `m.piaoxingqiu.com/cyy_gatewayapi/`
- 纷玩岛: `api.livelab.com.cn/performance/app/`
- 秀动 (ShowStart): `wap.showstart.com/`

## Notes

- This is a documentation repository, not a software project with build/test commands
- Content is primarily in Chinese
- Notebooks can be viewed in VS Code with Jupyter extension or run with `jupyter notebook`
