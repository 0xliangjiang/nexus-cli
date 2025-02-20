
# Nexus CLI 安装脚本

### 简介
这是一个用于安装 Nexus CLI 及其所需依赖的自动化脚本。该脚本会自动完成所有必要的环境配置。

### 前置要求
- 我用的是Ubuntu 24.04系统
- Sudo 权限
- 网络连接

### 一键执行脚本
```shell
wget -O nexus-cli.sh https://raw.githubusercontent.com/0xliangjiang/nexus-cli/refs/heads/main/nexus-cli.sh && sed -i 's/\r$//' nexus-cli.sh && chmod +x nexus-cli.sh && ./nexus-cli.sh
```
