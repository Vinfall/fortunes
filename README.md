# fortune-mod

中文版介绍见 [README_zh-Hans](README_zh-Hans.md)

Just some random fortune files I collected from wherever whoever knows.

## List

- [VNDB Quotes](vndb/), created using [fortunes-vndb](https://github.com/Vinfall/fortunes-vndb), check that repo for details.
- ~~Megasuki~~ [Mesugaki Dialogues](mesugaki/), sources
  - [雌小鬼对话包](https://steamcommunity.com/sharedfiles/filedetails/?id=3023130450) from VPet-Simulator Steam Workshop

## Usage

0. Note that it may contain NSFW content or **spoilers** so use it at your own risk
1. Install `fortune-mod` or `fortunes` from your package manager
2. Copy respective fortune files (e.g. `vndb` AND `vndb.dat`) to `/usr/share/fortunes` (or `/usr/share/games/fortunes`)
3. You can now use VNDB quote via `fortune vndb`

Example install commands:

```sh
$ sudo cp ./vndb* /usr/share/fortunes/

$ fortune vndb
I spent all of last year's Shiomi Festival participating in a self-sponsored Reading Festival at my apartment, actually.
        -- 筧 京太郎, Daitoshokan no Hitsujikai (https://vndb.org/v8158)
```
