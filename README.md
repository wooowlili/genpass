## 介绍

命令行密码生成工具，已在macOS和Linux上进行测试并长久使用

## 使用方式

### 方式一 手动构建

```bash
git clone git@github.com/wooowlili/genpass.git
cd genpass
go mod tidy
go build -o genpass
# 将编译好的文件移动到系统的PATH目录（如：/usr/bin/）
mv genpass /usr/bin/
```

### 方式二 直接下载预编译的二进制文件

1. 进入Release，下载对应系统的二进制文件
2. 将下载的文件移动到系统的PATH目录（如：/usr/bin/）
