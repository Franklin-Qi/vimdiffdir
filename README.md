# vimdiffdir

> 此脚本利用 `vimdiff` 在命令行下对文件夹下的文件进行递归式的对比，可以替代掉meld。

## 简介

* 依赖：`vimdiff` `diff`
* 功能：递归对比两个文件夹下的文件差异
* 操作要求：`vimdiff` 基本操作

## 使用说明

### 安装
```shell
git clone git@github.com:Franklin-Qi/vimdiffdir.git 

cd vimdiffdir && chmod +x ./vimdiffdir
sudo cp ./vimdiffdir /usr/bin/
```

### 示例

```shell
vimdiffdir dir1 dir2
```

如果文件夹下有多文件差异，只需在 `vim` 的命令模式下，键入 `qa` 即可进入下一对文件对比结果界面。


### vimdiff 基本操作

#### 合并操作

```
dp  将当前文件的差异put推送合并到另一文件
do  当前文件obtain获取合并另一文件差异

[c  跳到上一个差异点
]c  跳到下一个差异点

zo  打开折叠
zc  关闭折叠

:qa 进入下一个文件比对结果界面

```


