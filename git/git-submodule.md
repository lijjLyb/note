[【git Submodule管理项目子模块】](https://www.cnblogs.com/nicksheng/p/6201711.html)
[【git submodule 的使用】](https://blog.csdn.net/wangjia55/article/details/24400501)

当项目越来越庞大之后，不可避免的要拆分成多个子模块，我们希望各个子模块有独立的版本管理，并且由专门的人去维护，这时候我们就要用到git的submodule功能。

## 常用命令

```sh
git clone <repository> --recursive 递归的方式克隆整个项目
git submodule add <repository> <path> 添加子模块
git submodule init 初始化子模块
git submodule update 更新子模块
git submodule foreach git pull 拉取所有子模块
```