# Play 中文文档

[![Join the chat at https://gitter.im/Hawstein/play-for-scala-developers](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Hawstein/play-for-scala-developers?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Play 的 Scala API 在 play.api 包中。

> play 包中的 API 是为 Java 开发者准备的，比如 play.mvc。对于 Scala 开发者，请使用 play.api.mvc。

## 参与翻译

首先，你得有个 Github 账号，然后：

via google translate:

Participation translation

First, you have to have a Github account, then:

Open this project, Mengchuo "Fork" button
Fork to account under the item to your local Clone: ​​git clone git@github.com: your account name /play-for-scala-developers.git
In the project directory, create a new branch, such as the new branch named dev, then: git branch dev
Switch to the new branch: git checkout dev
Run git remote add upstream https://github.com/Hawstein/play-for-scala-developers.git the original project library add upstream library for synchronizing the latest content
Translation work in the dev branch, for example, you make changes (Play Doc: https: //www.playframework.com/documentation/2.3.x/ScalaHome) on ScalaRock.md
Submit your work: git add ScalaRock.md, then git commit -m 'translation ScalaRock'. In the process, you can use git status to view the status
Run git remote update update
Run git fetch upstream master pulling the upstream update to the local library
Run git rebase upstream / master database will be updated upstream into your dev branch
Run git push origin dev: master submitting your push to your library
Login Github, in your project page Fork has a "Pull Request" button, click on it, fill in some description, and then submit
Repeat steps 6-12
To avoid duplicate translation than the same chapter, first performed in front of the translation section of the claim. You can claim the post http://scalachina.org/topic/5501c59784ddfe6644e8c8d4 reply in the corresponding sections, you can also add QQ group, in the group said. Group number: 312 213 800.

Claim and complete. See: http://scalachina.org/topic/5501c59784ddfe6644e8c8d4

Terminology Chart

The following table is a term used to translate documents, such doubt or choose a better translation, please submit Pull Requests.

English Chinese
controller controller
type class





1. 打开[这个项目](https://github.com/Hawstein/play-for-scala-developers)，猛戳「Fork」按钮
1. 把 Fork 到你账号下的项目 Clone 到本地：git clone git@github.com:你的账号名/play-for-scala-developers.git
1. 在项目目录下，创建一个新分支来工作，比如新分支名叫 dev，则：git branch dev
1. 切换到新分支：git checkout dev
1. 运行 git remote add upstream https://github.com/Hawstein/play-for-scala-developers.git 把原始项目库添加为上游库，用于同步最新内容
1. 在 dev 分支下进行翻译工作，比如你在 ScalaRock.md 上做修改（Play Doc：https://www.playframework.com/documentation/2.3.x/ScalaHome）
1. 提交你的工作：git add ScalaRock.md，然后 git commit -m '翻译 ScalaRock'。在这些过程中，你都可以用 git status 查看状态
1. 运行 git remote update 更新
1. 运行 git fetch upstream master 拉取上游库的更新到本地
1. 运行 git rebase upstream/master 将上游库的更新合并到你的 dev 分支
1. 运行 git push origin dev:master 将你的提交 push 到你的库中
1. 登录 Github，在你 Fork 的项目页有个 「Pull Request」按钮，点击它，填写一些说明，然后提交
1. 重复步骤 6～12

为了避免多人重复翻译同一章节，在翻译前先进行章节的认领。可以在帖子 http://scalachina.org/topic/5501c59784ddfe6644e8c8d4 回复里认领相应章节，也可以加 QQ 群，在群里说。群号：312213800。

认领及完成情况见： http://scalachina.org/topic/5501c59784ddfe6644e8c8d4

## 术语对照表

下面是翻译文档的术语对照表，如有疑义或更好的翻译选择，欢迎提交 Pull Requests。

| 英文        | 中文   |
| --------   | -----  |
| controller | 控制器 |
| type class | 类型类 |
