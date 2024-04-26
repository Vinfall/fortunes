# fortune-mod

我从角落旮笪收集的一些奇怪 fortune files。

## 列表

- [VNDB Quotes](vndb/)，使用 [fortunes-vndb](https://github.com/Vinfall/fortunes-vndb) 生成，详情见对应仓库
- [雌小鬼对话](mesugaki/)，来源
  - [雌小鬼对话包](https://steamcommunity.com/sharedfiles/filedetails/?id=3023130450)，来自虚拟桌宠模拟器 Steam 创意工坊

## 使用

0. 注意可能包含 NSFW 或**剧透**内容，建议酌情使用
1. 使用软件包管理器安装 `fortune-mod` 或 `fortunes`
2. 将对应 fortune files（例如 `vndb` **和** `vndb.dat`）复制到 `/usr/share/fortunes`（或 `/usr/share/games/fortunes`）
3. 现在即可通过 `fortune vndb` 等命令使用对应 fortune

示例安装命令:

```sh
$ sudo cp ./vndb* /usr/share/fortunes/

$ fortune vndb
I spent all of last year's Shiomi Festival participating in a self-sponsored Reading Festival at my apartment, actually.
        -- 筧 京太郎, Daitoshokan no Hitsujikai (https://vndb.org/v8158)
```
