# <p align="center">使用Laya引擎开发的联网麻将游戏</p>

## 🔥 [服务端仓库地址](https://github.com/liumengniu/majiang-server)
## 🔥 [直接上手？文档地址？点这里](https://liumengniu.github.io/majiang-server/)
## 🔥 此项目长期维护，有任何问题 [请提交 issue](https://github.com/liumengniu/majiang/issues)， 或者通过issue留下联系方式。

[//]: # (https://github.com/ikatyang/emoji-cheat-sheet 表情仓库)


## 🎞️ 项目介绍

> 使用laya3.x游戏引擎开发的联网棋牌游戏。 \
> 以下是通过项目生成的原始示例，未经任何修改：
> ![img.png](./screenshot/麻将.gif)


## 🎨 项目结构

```
├── majiang                # 麻将
├── assets                 # 静态资源目录
├── bin                    # 测试运行的index.html首页的入口，以及IDE内置的代码入口（如html/bundle.js）
├── engine                 # 引擎库的声名文件 - 开发不要动
├── library                # 开发不要动
├── settings               # 游戏配置项 - 开发不要动
├── src                    # 项目源码目录（√核心）
│   ├── prefab/               # 预制体相关ts代码的集合   
│   ├── configs/              # 公共配置
│   ├── utils/                # 公共工具类
│   │   ├── HandleReceivedMessage.ts    # 执行服务端的消息
│   │   ├── HttpHelper.ts               # http短连接公共类
│   │   ├── SocketHelper.ts             # websocket长连接公共类
│   ├── HallScript.ts         # 大厅场景自定义脚本   
│   ├── HallRT.ts             # 大厅场景UI运行时脚本 
│   ├── HallRT.generated.ts   # 大厅场景UI运行时脚本基础类 
│   ├── LoginScript.ts        # 登录场景自定义脚本
│   ├── Main.ts               # 游戏场景自定义脚本（√最主要的脚本，游戏逻辑都在此）   
│   ├── MainRT.ts             # 游戏场景UI运行时脚本   
│   └── MainRT.generated.ts   # 游戏场景UI运行时脚本基础类   
├── .gitignore             # git忽略配置
├── package.json           # 依赖表
└── tsconfig.json          # ts配置文件
```

## 💡 正在开发中的内容

> 正在开发的内容 2024/9/29 
>

| 蓝图                         | 完成情况       | 存在问题        |
|-----------------------------|------------|-------------|
| 1、登录注册                   | 已完成     | 暂无  |
| 2、开房/加入房间/解散房间        | 已完成     | 暂无  |
| 3、游戏全过程                  | 已完成     | 暂无  |
| 4、碰/杠/胡/流局               | 已完成     | 暂无  |
| 5、AI自动出牌                  | 已完成     | 暂无  |
| 6、胡牌/平局结算               | 已完成     | 暂无  |
| 7、掉线重新加入游戏             | 已完成     | 暂无  |
| 8、基础服务和棋牌玩法逻辑抽离     | 已完成     | 暂无  |
| 9、其它功能                    | 已完成     | 暂无  |
| 10、更详细的文档                | 开发中     | 暂无  |
| 11、扑克游戏（升级or斗地主）     | 开发中     | 暂无  |

## 🌟 Star History
<br>


[![Star History Chart](https://api.star-history.com/svg?repos=liumengniu/majiang&type=Timeline)](https://api.star-history.com/svg?repos=liumengniu/majiang&type=Timeline)