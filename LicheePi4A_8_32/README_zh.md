# Lichee Pi 4A

## 测试环境

### 操作系统信息

- openEuler 24.03 LTS SP1
    - 下载链接：https://mirrors.tuna.tsinghua.edu.cn/openeuler/openEuler-24.03-LTS-SP1/embedded_img/riscv64/lpi4a/
    - 参考安装文档：https://docs.openeuler.org/zh/docs/24.03_LTS_SP1/docs/Installation/RISC-V-LicheePi4A.html
- openEuler RISC-V 25.03
    - 下载链接： https://repo.openeuler.org/openEuler-25.03/embedded_img/riscv64/lpi4a/
    - 参考安装文档：https://docs.openeuler.org/en/docs/24.03_LTS/docs/Installation/RISC-V-LicheePi4A.html
- openKylin 2.0 SP1
    - 下载链接：https://www.openkylin.top/downloads/index-cn.html
    - 参考安装文档：https://docs.openkylin.top/zh/01_%E5%AE%89%E8%A3%85%E5%8D%87%E7%BA%A7%E6%8C%87%E5%8D%97/%E5%9C%A8riscv%E4%B8%8A%E5%AE%89%E8%A3%85/%E5%9C%A8LicheePi4A%E4%B8%8A%E5%AE%89%E8%A3%85openKylin
- Armbian 23.09.15
    - 下载链接：https://github.com/chainsx/armbian-riscv-build/releases
    - 参考安装文档：https://github.com/chainsx/armbian-riscv-build/blob/main/doc/licheepi-4a-install-guide.md
- Arch Linux
    - 下载链接：https://mirror.iscas.ac.cn/archriscv/images/
    - 参考安装文档：https://wiki.archlinux.org/title/General_recommendations
- NixOS
    - 下载链接：https://github.com/ryan4yin/nixos-licheepi4a/releases
    - 参考安装文档：https://github.com/ryan4yin/nixos-licheepi4a
- Slackware
    - 下载链接：http://dl.slarm64.org/slackware/images/lichee_pi_4a/
    - 参考安装文档：http://dl.slarm64.org/slackware/images/lichee_pi_4a/README.TXT
- Fedora 38
    - 下载链接：https://github.com/chainsx/fedora-riscv-builder/releases
    - 参考安装文档：https://wiki.sipeed.com/hardware/zh/lichee/th1520/lpi4a/4_burn_image.html
- OpenWRT
    - 下载链接：https://github.com/chainsx/openwrt-th1520/releases
    - 参考安装文档：https://github.com/chainsx/armbian-riscv-build/blob/main/doc/licheepi-4a-install-guide_ch.md
- Deepin 25-beige-preview 20250122
    - 下载链接：https://deepin-community.github.io/sig-deepin-ports/images/riscv/download
    - 参考安装文档：https://cdimage.deepin.com/RISC-V/preview-20240517-riscv64/README.md
- RevyOS 20250323
    - 下载链接：https://fast-mirror.isrc.ac.cn/revyos/extra/images/lpi4a/20250323/
    - 参考安装文档：https://revyos.github.io/docs/

### 硬件开发板信息

- Lichee Pi 4A 8GB RAM + 32GB eMMC

## 测试结果

| 软件分类                       | 软件包名 | 测试结果（测试报告）          |
|--------------------------------|----------|-------------------------------|
| openEuler/Base 镜像启动        | N/A      | [成功][oERV]                  |
| openEuler/Xfce 镜像启动        | Xfce     | [成功][oERV]                  |
| openEuler 社区创新版本镜像启动 | N/A      | [成功][openEuler]             |
| Armbian(Ubuntu) 桌面镜像启动   | Xfce     | [成功][Armbian]               |
| Fedora chainsx 桌面镜像启动    | N/A      | [成功][Fedora]                |
| openKylin 桌面镜像启动         | N/A      | [成功][openKylin]（官方支持） |
| OpenWRT 镜像启动               | N/A      | [成功][OpenWRT]               |
| Arch Linux 桌面镜像启动        | N/A      | [成功][ArchLinux]             |
| NixOS 镜像启动                 | N/A      | [成功][NixOS]                 |
| Slackware 镜像启动             | N/A      | [成功][Slackware]             |
| Deepin 桌面镜像启动            | N/A      | [成功][Deepin]                |
| RevyOS 桌面镜像启动            | N/A      | [成功][RevyOS]                |


[oERV]: ./openEuler/README_zh.md
[openEuler]: ./openEuler/Innovation_zh.md
[Fedora]: ./Fedora/README_chainsx_zh.md
[Armbian]: ./Armbian/README_zh.md
[openKylin]: ./openKylin/README_zh.md
[OpenWRT]: ./OpenWRT/README_zh.md
[ArchLinux]: ./ArchLinux/README_zh.md
[Deepin]: ./Deepin/README_zh.md
[RevyOS]: ./RevyOS/README_zh.md
[NixOS]: ./NixOS/README_zh.md
[Slackware]: ./Slackware/README_zh.md
