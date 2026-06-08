# 进入设备树的上两级目录（也就是包含 device 文件夹的那个目录）
cd /root/twrp   # 或者你存放 device 的父目录

# 初始化 git 仓库
git init
git add device/oppo/PGGM10
git commit -m "Add PGGM10 device tree and kernel Image"

# 关联远程仓库（把下面网址换成你自己的仓库地址，注意大小写）
git remote add origin https://github.com/lanlanhangxian-cpu/PGGM10_TWRP.git

# 推送到 GitHub（会提示输入用户名和密码/令牌）
git branch -M main
git push -u origin main# PGGM10_TWRP
