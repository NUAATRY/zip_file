# 阅读文件

- first commit:上传了根文件系统roots-hbb.tar.bz2，该文件系统是通过bisybox生成的。上传了uboot-imx-rel-hbb.tar.bz2,该文件是NXP提供的Uboot文件结合正点原子修改而成，适配IMX6uLL系列的板子

- add gitignore:将linux-imx-rel-hbb.tar.bz2放在了ignore文件夹下，因为文件太大不能上传到github官网上,该文件是根据NXP提供的Linux内核修改成了适配IMX6ULL系列板子的内核，主要内容是修改网络驱动，显示屏，时钟等。
