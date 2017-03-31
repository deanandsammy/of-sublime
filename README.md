# of-sublime

sublime-text3 windows下的使用经验分享
![img](https://github.com/elegantspirit/of-sublime/blob/master/assets/sublime.jpg)

## 入门

- [Sublime Text](http://www.sublimetext.com/) - 官方下载地址
- [key bindings](https://github.com/elegantspirit/of-sublime/blob/master/assets/key-bindings.md) - 我的sublime-text3快捷键，移植自个人的 webstorm 快捷键，一定程度上提高了代码输入的效率，关键是使用起来很顺手
## UI theme

- [Boxy theme](https://github.com/ihodev/sublime-boxy) - 最喜欢的一款主题，简单丰富，关键是不折腾

## 常用插件推荐

- [sublimecodeintel](https://github.com/SublimeCodeIntel/SublimeCodeIntel/)  全能的代码智能提示插件
- javascript completions 强烈推荐，会有API提示

  ![javascript completions](https://github.com/elegantspirit/of-sublime/blob/master/assets/javascript-completions.png)
- autosave 
  此插件自动保存功能默认处于关闭状态，preference -> key bindings -> default.sublime-keymap-user 中写入下面代码，`{ "keys": ["ctrl+shift+s"], "command": "auto_save" }`，ctrl+shift+s 打开自动保存功能。也可以 ctrl+shift+p 打开插件安装窗口，输入 autosave，选择需要保存的文件。
  
  ![autosave-plugin](https://github.com/elegantspirit/of-sublime/blob/master/assets/autosave-plugin.png)
  
- [emmet](https://github.com/sergeche/emmet-sublime)  &emsp;前身是 Zen Coding）是一个前端开发不可缺少的插件，它让编写 HTML和CSS代码变得如此简单，节省了大量时间。Emmet 可使开发者用缩写形式书写代码，再用“扩展”功能自动将代码扩展至完整样式。
