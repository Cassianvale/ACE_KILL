<!-- markdownlint-restore -->
<div align="center">

# ACE-KILLER

✨**TX Games 游戏进程优化工具**✨

*本项目主要为了优化ACE扫盘进程，以提升游戏帧率和稳定性*
<br>
*适用于无畏契约、三角洲行动等TX游戏*

</div>
<!-- markdownlint-restore -->

## 🍉 主要功能

- 自定义游戏功能  
- 自动关闭`ACE-Tray.exe`安装提示  
- 自动设置扫盘进程`SGuard64.exe`优先级为空闲&单小核运行  
- 显示状态功能  
- 开机自启功能  
- 开启/关闭Windows消息通知功能  
- 优化后很小的资源占用率  

<img src="https://github.com/Cassianvale/ACE-KILLER/raw/main/assets/image/1.png" alt="1" style="zoom: 50%;" /> <!-- markdownlint-disable-line MD033 -->
<img src="https://github.com/Cassianvale/ACE-KILLER/raw/main/assets/image/2.png" alt="2" style="zoom: 50%;" /> <!-- markdownlint-disable-line MD033 -->


## 🌏 直接下载  

您可以从以下位置下载最新版本：  

- [最新版本下载](https://github.com/Cassianvale/ACE-KILLER/releases/latest)  
- [查看所有版本](https://github.com/Cassianvale/ACE-KILLER/releases)  

> 注意：请始终从 GitHub Releases 页面下载最新版本，以确保获得最新的功能和安全更新。  

## 😼 如何自定义游戏


```yaml
games:
  # 自定义游戏名称
  - name: 无畏契约
    # 登陆器可执行文件的名称
    launcher: 无畏契约登录器.exe
    # 主游戏进程名
    main_game: VALORANT-Win64-Shipping.exe
    # 是否启用该游戏配置（true 表示启用，false 表示禁用）
    enabled: true
```

## 📦 如何打包

1. 安装依赖：  
```bash
pip install -r requirements.txt
```

2. 运行打包脚本：  
```bash
python build_exe.py
```

3. 打包完成后，生成`main.dist`打包输出目录以及`.zip`压缩文件

## 📢 免责声明  
- **仅供个人学习研究使用，禁止用于商业及非法用途**  
- **开发者拥有本项目的最终解释权**  
- **严禁用于任何违反`中华人民共和国(含台湾省)`或使用者所在地区法律法规的用途**  
- **请使用者在使用本项目时遵守相关法律法规，不要将本项目用于任何商业及非法用途。如有违反，一切后果由使用者自负。 同时，使用者应该自行承担因使用本项目而带来的风险和责任。本项目开发者不对本项目所提供的服务和内容做出任何保证**  
- **若您遇到商家使用本软件进行收费，产生的任何问题及后果与本项目无关**  

## 📜 开源许可
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)  

ACE-KILLER 使用 [GNU General Public License v3.0](LICENSE) 开源许可证  

Copyright © 2025 by Cassianvale.  