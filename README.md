# 把你的Linux美化成Ubuntu Gnome


### 效果图

![输入图片说明](%E6%88%AA%E5%9B%BE%202024-12-12%2009-11-38.png)

### 材料

1. 一台Linux电脑
2. Gnome桌面
3. Yaru主题包

### 第一步、下载主题包

来这里 [输入链接说明](https://github.com/ubuntu/yaru) 下载Yaru主题包。

![输入图片说明](%E5%9B%BE%E7%89%87.png)

### 解压 

![输入图片说明](%E5%9B%BE%E7%89%871.png)

### 下载 meson 和 ninja


```
# Debian
sudo apt install meson

# Arch
sudo pacman -S meson ninja
```

### 进入目录

![输入图片说明](%E5%9B%BE%E7%89%872.png)

### 右键进入命令行

![输入图片说明](%E5%9B%BE%E7%89%873.png)

![输入图片说明](%E5%9B%BE%E7%89%874.png)

### 输入这个命令


```
unzip yaru-master.zip # 解压主题包

cd yaru-master # 进入文件夹

meson build # 创建构建环境

cd build # 进入配置环境

ninja # 开始配置

ninja install # 安装
```

期间会要求输入密码，输入即可。

### 安装 dash to dock

来到这个网站

![输入图片说明](%E5%9B%BE%E7%89%875.png)

输入 dash to dock

![输入图片说明](%E5%9B%BE%E7%89%876.png)

选它

![输入图片说明](%E5%9B%BE%E7%89%877.png)

![输入图片说明](%E5%9B%BE%E7%89%878.png)

进入设置

![输入图片说明](%E5%9B%BE%E7%89%879.png)

![输入图片说明](%E5%9B%BE%E7%89%8710.png)

按照图片中这样选

![输入图片说明](%E5%9B%BE%E7%89%8711.png)

![输入图片说明](%E5%9B%BE%E7%89%8712.png)

进入tweak工具

![输入图片说明](%E5%9B%BE%E7%89%8713.png)

按照图片中这样选

![输入图片说明](%E5%9B%BE%E7%89%8714.png)

（PS：不喜欢暗色可以选非Dark结尾那个）

gnome4x开始使用libwaita作为系统应用的主题库，目前并没有办法在优化里控制暗色和亮色，不过可以在菜单这里控制

![输入图片说明](%E5%9B%BE%E7%89%8715.png)

### 雕刻细节

现在，你的界面大致轮廓已经很像了，但是还没有到一模一样的程度，你还需要一些精雕细琢。

你打开终端，复制下面这段指令。


```
cd /usr/share/icons/Yaru/scalable/actions
sudo cp -rf view-app-grid-ubiquity-symbolic.svg view-app-grid-symbolic.svg
```

然后再加上这些插件

![输入图片说明](%E5%9B%BE%E7%89%8716.png)

![输入图片说明](%E5%9B%BE%E7%89%8717.png)

这样配置

![输入图片说明](%E5%9B%BE%E7%89%8718.png)

