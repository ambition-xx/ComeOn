# ComeOn
第四届青训营ComeOn队抖音项目
## 提交
commit message 应当遵守以下格式：
```
类型: 描述
```
其中「类型」可以是以下的其中一种：
```
# 主要type
feat:     增加新功能
fix:      修复bug

# 特殊type
docs:     只改动了文档相关的内容
style:    不影响代码含义的改动，例如去掉空格、改变缩进、增删分号
build:    构造工具的或者外部依赖的改动，例如webpack，npm
refactor: 代码重构时使用
revert:   执行git revert打印的message

# 暂不使用type
test:     添加测试或者修改现有测试
perf:     提高性能的改动
ci:       与CI（持续集成服务）有关的改动
chore:    不修改src或者test的其余修改，例如构建过程或辅助工具的变动
```
**多提交！** 每一项工作都应该尽量是一个独立的 commit，不要把 bugfix 和 feature 杂糅在一个 commit 里提交，不要连续写好几天不提交最后一起提交！

每个 commit 只应该做 commit message 里提到的事情，不应该额外动到其他部分的任何代码。在动手写代码之前，先想清楚你这一次要干什么，干完那件事情，测试完成后，马上提交！然后再开始下一件事情。

push 之前，记得先 `git fetch` 或 `git pull --rebase`，确保远端没有任何本地没有的新提交，然后再 push。禁止使用 force push。
