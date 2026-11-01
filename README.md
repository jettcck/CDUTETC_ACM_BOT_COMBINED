# CDUTETC ACM Bot Combined

这个仓库把三个项目放在同一个代码仓库中，目录彼此独立：

- [AstrBot](./AstrBot/)：AstrBot 主项目，来源于 https://github.com/AstrBotDevs/AstrBot
- [CDUTETC_ACM_BOT](./CDUTETC_ACM_BOT/)：CDUTETC ACM 事务助手，来源于 https://github.com/heqiuyu209/CDUTETC_ACM_BOT
- [dsh-qqbot](./dsh-qqbot/)：QQ Bot 接入项目，来源于 https://github.com/tencent-connect/dsh-qqbot

## 目录关系

三个子目录保留各自的依赖、配置和启动方式。组合仓库不把三个项目的运行时依赖混在一起，也不覆盖任何一个项目的入口文件。

## 使用方式

进入对应子目录后，按照该项目自己的 README 安装和启动：

```powershell
Set-Location .\AstrBot
# 按 AstrBot/README.md 操作

Set-Location ..\CDUTETC_ACM_BOT
# 按 CDUTETC_ACM_BOT/README.md 操作

Set-Location ..\dsh-qqbot
# 按 dsh-qqbot/README.md 操作
```

## 来源

本组合仓库使用三个项目各自默认分支的源码快照生成。后续更新某个子项目时，请在对应目录单独同步上游变更，并检查其配置和依赖是否仍然兼容。
