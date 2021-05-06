# Golang

## 安装

安装参见 [Downloads](https://golang.google.cn/dl/)

## 初始化

创建 GOPATH

    mkdir -pv $(go env GOPATH)

修改部分 go envs

    go env -w GOPROXY=https://goproxy.baidu.com,https://proxy.golang.org,direct
    go env -w GO111MODULE=on
