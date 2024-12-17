# task-tracker

## 1. 项目简介

一个简单的任务跟踪系统，支持用户注册、登录、创建任务、查看任务、修改任务状态、删除任务等功能。

## 2. 项目结构

```go
task-tracker
├── README.md
├── cmd
│   └── task-tracker
│       └── main.go
├── go.mod
├── go.sum
└── internal
    ├── ctrl
    │   └── task.go
    ├── model
    │   └── task.go
    ├── router
    │   └── router.go
    └── service
        └── task.go
```
