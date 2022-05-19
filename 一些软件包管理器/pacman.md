# Pacman

pacman是一种软件包管理工具，在Arch Linux以及其衍生发行版中被使用。

> 常用的软件包后缀 **\*.pkg.tar.zst**

一些常用的命令：  
（以下用"*"来指代软件包的名称）

- pacman -S * 安装一个软件
- pacman -R * 卸载一个软件

---

- pacman -Ss * 搜索一个软件
- pacman -Sy 刷新软件列表
- pacman -Syu 刷新软件列表，并更新所有软件
- pacman -Syy 强制刷新软件列表
- pacman -Syyu 强制刷新软件列表，并更新所有软件
- pacman -Rs * 卸载一个软件，并移除它附带的所有不使用的依赖
