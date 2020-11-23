# scratch-gui 二次开发

## 修改记录 2020/10/29

### 修正在Win10下编译时的错误 （参见：https://github.com/LLK/scratch-blocks/issues/1620）

1. 修改build.py脚本， 修改开新进程相关部分代码
2. 修改package.json，指定python命令的绝对路径（临时方案，因为向path中添加python2安装路径毫无效果）
