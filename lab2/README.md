# lab2

### 编译

使用如下命令编译

	gcc -o sh shell.c

### 功能

**管道**

可支持多管道，如`ls | cat | wc`、`env | grep PATH | cat | wc`等。

**修改环境变量**

支持使用命令`export KEY=value`增加或改变环境变量。

**文件重定向**

支持文件重定向符号`>`、`>>`、`<`。

**健壮性**

可处理多空格的输入。