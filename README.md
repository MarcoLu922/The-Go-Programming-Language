# The-Go-Programming-Language

## Go语言特性

- 静态类型和编译型语言
- 垃圾回收机制
- 原生并发支持（goroutine和channel）
- 简洁高效的语法
- 跨平台编译能力

## 环境安装

- 访问[官网下载](https://golang.google.cn/dl/)
- 解压到指定目录
- 设置环境变量
- 验证安装：`go version`
- 配置Go环境变量：
- 添加以下内容到系统环境变量：

- ```bash
  GOROOT=C:\Go\go
  GOPATH=C:\Users\YourName\go
  PATH=%PATH%;%GOROOT%\bin;%GOPATH%\bin
  ```

- 验证配置：`go env`
- 创建工作目录：`mkdir go-project`
- 进入工作目录：`cd go-project`
- 创建Go模块：`go mod init mymodule`
- 编写Go代码：`vim main.go`
- 编译和运行：`go run main.go`
- 安装依赖：`go get package`
- 构建可执行文件：`go build main.go`
- 运行可执行文件：`./main`

## 基本语法

- 变量声明：`var name type = value`
- 常量声明：`const name = value`
- 函数定义：`func name(parameters) returnType { ... }`
- 控制结构：`if`, `for`, `switch`
- 指针：`*`
- 结构体：`type structName struct {... }`
- 接口：`type interfaceName interface {... }`
- 错误处理：`error`
- 并发：`goroutine`, `channel`
- 包管理：`import`, `go mod`
- 测试：`go test`
- 反射：`reflect`
- 标准库：`fmt`, `net/http`, `os`, `strings`, `math`
- 第三方库：`github.com/...`
