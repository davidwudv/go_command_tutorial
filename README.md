# Go 命令教程
## 目录

 - [标准命令详解](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.0.md)
 - [go build](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.1.md)
 - [go install](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.2.md)
 - [go get](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.3.md)
 - [go clean](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.4.md)
 - [go doc与godoc](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.5.md)
 - [go run](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.6.md)
 - [go test](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.7.md)
 - [go list](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.8.md)
 - [go fmt与gofmt](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.9.md)
 - [go fix与go tool fix](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.10.md)
 - [go vet与go tool vet](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.11.md)
 - [go tool pprof](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.12.md)
 - [go tool cgo](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.13.md)
 - [go env](https://github.com/hyper-carrot/go_command_tutorial/blob/master/0.14.md)

## 作者介绍

**郝林**，10年软件开发从业经验。搞过银行、电信软件和互联网社交等产品。对Go语言和Docker都情有独钟。现在正在从事互联网软件基础组件的构建以及Go语言的技术推广和社区运营等工作。他也是图灵原创技术图书《Go并发编程实战》和在线免费教程《Go语言第一课》的作者。

## 本教程的由来

这份Go命令教程原先是我著的图书[《Go并发编程实战》](http://www.ituring.com.cn/book/1525)中的一部分。这部分内容与并发编程的关系不大，故被砍掉。但是它是有价值的，也算是我对Go语言官方提供的标准命令的一个学习笔记。所以，我觉得应该把它做成免费资源分享给大家。经出版社的认可，我将这份教程放在这里供广大Go语言爱好者阅读。


## 相关源

本教程在Github上的地址在[这里](https://github.com/hyper-carrot/go_command_tutorial)。如果你喜欢本教程，请不吝Star。如果你想贡献一份力量，欢迎提交Pull Request。

针对Go 1.3和1.4版本的教程已被放入分支[go1.3](https://github.com/hyper-carrot/go_command_tutorial/tree/go1.3)。而主分支此后一段时间内会致力于针对Go 1.5进行更新。

本教程中会提及一个名为```goc2p```的项目。该项目实际上是《Go并发编程实战》随书附带的示例项目。这本书中讲到的所有源码都在```goc2p```项目中。我已在《Go并发编程实战》出版之时将[```goc2p```](https://github.com/hyper-carrot/goc2p)项目放出。

## 关于协议

我希望这个项目中的内容永远是免费的。也就是说，任何组织和个人不应该出于商业目的而摘取其中的内容。更详细的条款请阅读本项目中的[LICENSE](https://github.com/hyper-carrot/go_command_tutorial/blob/master/LICENSE)文件。

## 版本信息
书中内容及演示代码基于以下版本：

| 系统      | 版本信息
|---------|------
|Golang   |1.3(will be abandoned) + 1.5(in prograss)