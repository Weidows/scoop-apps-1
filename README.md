<p align="center">
  scoop-apps
</p>
<p align="center">
  <a href="https://github.com/kkzzhizhou/scoop-apps"><img alt="GitHub" src="https://img.shields.io/badge/Readme--Style-standard--repository-brightgreen?style=flat-square&color=f83500"/></a>
  <a href="https://github.com/kkzzhizhou/scoop-apps"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/kkzzhizhou/scoop-apps?style=flat-square"/></a>
  <a href="https://github.com/kkzzhizhou"><img alt="GitHub user" src="https://img.shields.io/badge/author-kkzzhizhou-brightgreen?style=flat-square"/></a>
</p>


## 介绍

此仓库每天自动合并其他scoop仓库的更新

## 特性

- 每天更新
- 仓库列表根据项目[scoop-directory](https://github.com/rasa/scoop-directory)动态生成
- 自动处理同名文件，优先采用同名文件的较新版本, 重名文件以"软件-贡献人ID"重命名
- 自动去重（基于md5)
- json格式检验

## 说明

- 可接受仓库推荐，提交pr至bucket-recommend.txt即可。
- 未对仓库软件来源进行安全检验，请自行甄别恶意软件，或者使用杀毒软件
- 不接受Pull requests，请参考仓库根路径的app-contributor-list.txt到相应的仓库提交pull requests
- 不接受不维护仓库清理等相关Issues

## 使用方法

```
scoop bucket add apps https://github.com/kkzzhizhou/scoop-apps
```

## FAQ

### 安装部分软件Hash Check Failed

可以使用`-s`忽略，比如`scoop install xxx -s`即可

## 感谢

- [scoop-directory](https://github.com/rasa/scoop-directory)

## 合并仓库列表

- kkzzhizhou/scoop-zapps
- HCLonely/my-scoop-bucket
- ScoopInstaller/Extras
- chawyehsu/dorado
- matthewjberger/scoop-nerd-fonts
- ScoopInstaller/Java
- TheRandomLabs/Scoop-Spotify
- Calinou/scoop-games
- TheRandomLabs/scoop-nonportable
- borger/scoop-galaxy-integrations
- ivaquero/scoopet
- TheCjw/scoop-retools
- ScoopInstaller/Versions
- kodybrown/scoop-nirsoft
- L-Trump/scoop-raresoft
- Ash258/Scoop-JetBrains
- littleli/scoop-clojure
- kidonng/sushi
- rasa/scoops
- MCOfficer/scoop-nirsoft
- KNOXDEV/wsl
- echoiron/echo-scoop
- hermanjustnu/scoop-emulators
- everyx/scoop-bucket
- cderv/r-bucket
- TheRandomLabs/Scoop-Bucket
- hoilc/scoop-lemon
- Paxxs/Cluttered-bucket
- scoopcn/scoopcn
- Qv2ray/mochi
- dodorz/scoop
- kiennq/scoop-misc
- ZvonimirSun/scoop-iszy
- zhoujin7/tomato
- wzv5/ScoopBucket
- borger/scoop-emulators
- ACooper81/scoop-apps
- TheRandomLabs/Scoop-Python
- naderi/scoop-bucket
- ChungZH/peach
- 42wim/scoop-bucket
- ScoopInstaller/Nonportable
- krproject/qi-windows
- excitoon/scoop-user
- batkiz/backit
- jfut/scoop-jfut
- mogeko/scoop-sysinternals
- iquiw/scoop-bucket
- MCOfficer/scoop-bucket
- littleli/Scoop-littleli
- Apocalypsor/My-Scoop-Bucket
- Velgus/Scoop-Portapps
- ChinLong/scoop-customize
- Darkatse/Scoop-Darkatse
- seumsc/scoop-seu
- rivy/scoop-bucket
- ddavness/scoop-roblox
- alextwothousand/scoop-bucket
- nickbudi/scoop-bucket
- Darkatse/Scoop-KanColle
