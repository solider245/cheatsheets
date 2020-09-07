# `cheatsheets`

该存储库包含社区来源的 [备忘单](https://github.com/cheat/cheat) ， 可与 [备忘](https://github.com/cheat/cheat) 和类似应用程序一起使用。

### `Format`

备忘单是纯文本文件，其开头是YAML格式的可选“前件”标题。 首标可以被用于分配的“标记”的片材，并以指定的纸张的语法（ `bash` ， `python` ， `go` 等）。

速查表应尽可能遵循以下格式：

```shell
---
syntax: bash
tags: [ vcs, development ]
---
# To stage all changes in the current directory:
git add --all

# To commit staged changes:
git commit -m <message>
```

作为准则， 在指定参数占位符时 ，最好使用 [docopt](http://docopt.org) 语法。 在边沿的情况下该语法可能会引起混淆，它允许使用占位符值（ `foo.txt` ， `example.com` 等）是必要的。

### `License`

备忘单是根据 [知识共享CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/legalcode) 许可的 。 有关 完整的许可证文本， 请参阅 [LICENSE.txt](https://github.com/cheat/cheatsheets/blob/master/.github/LICENSE.txt) 。
