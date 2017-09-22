# 系统差异

## 简介

Cocos Studio 是一个跨平台的游戏编辑器，为了保证操作的统一，编辑器通过技术手段解决系统间的差异，尽力统一用户的操作体验。但限于操作系统的限制，部分操作仍将无法实现统一。如文件的路径，在不同的系统内使用的是完全不同的管理方式。对于这部分问题将统一记录在本页面。

#### 菜单栏

在"Windows"系统下，Cocos Studio的菜单栏位于编辑器界面的顶部,工具栏的上方。在"OS X"系统下，Cocos Studio的菜单栏同多数"OS X"应用一样，位于操作系统的菜单栏内，通常操作系统的菜单栏位于窗口的顶部。

### 文件路径

在"Windows"系统下，操作系统会分配多个盘符，每个盘符都将是独立的。路径类似"D:\cocos\"，文件夹间以"\"作为分隔符。在"OS X"系统下，操作提供没有盘符的概念，所有的内容都将以"/"为根路径。在配置编辑器属性或者通过编辑器打开,引入,保存文件时，请注意文件路径的差异，特别在手动输入文件路径的时候。