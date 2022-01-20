# Fcitx5Themes

使用 [ssfconv](https://github.com/fkxxyz/ssfconv) 工具从[搜狗皮肤](https://pinyin.sogou.com/skins/)转换得到的几款 Fcitx5 主题。

### 【十月】诗与远方
![【十月】诗与远方](.img/【十月】诗与远方.png)


### 【十月】长草颜团子：打团子糕咯！
![【十月】长草颜团子：打团子糕咯！](.img/【十月】长草颜团子：打团子糕咯！.png)


### 【囍】吹吖吹吖！
![【囍】吹吖吹吖！](.img/【囍】吹吖吹吖！.png)


### 【悠然】长草颜团子·下雨啦
![【悠然】长草颜团子·下雨啦](.img/【悠然】长草颜团子·下雨啦.png)


### 【景诺】长草颜团子·起来嗨
![【景诺】长草颜团子·起来嗨](.img/【景诺】长草颜团子·起来嗨.png)


### 【魔道祖师】江澄·生日
![【魔道祖师】江澄·生日](.img/【魔道祖师】江澄·生日.png)


# 安装
1. 将感兴趣的主题文件夹拷贝到路径 `~/.local/share/fcitx5/themes/` 下；
2. 然后打开「fcitx5 配置」，选择「配置附加组件」->「经典用户界面栏」->「配置」->「主题」，换上自己已拷贝的主题即可；
3. 如果不想 GUI 操作，也可以直接修改文件 `~/.config/fcitx5/conf/classicui.conf`：
```bash
# 替换下面《你喜欢的主题名称》为你要更换的主题名称
sed -i 's/^Theme=.*$/Theme=《你喜欢的主题名称》/' ~/.config/fcitx5/conf/classicui.conf
```