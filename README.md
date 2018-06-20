# master-dissertation

硕士学位论文。

1. 使用了 TeX Live 2018 自带的模板 hithesis，该模板非最新版。最新版的网址为 https://github.com/dustincys/hithesis 。
2. 更改了原授权页，并添加了新的授权页。具体地，更改了文件 hithesis.cfg 和 hithesis.cls 的相关文字授权说明，以变更原有授权页；仿照 `\authorization` 和 `\authorization[saomiao.pdf]`，添加了 `\authorizationSUST` 和 `\authorizationSUST[saomiao.pdf]` 两个命令，用来生成新的授权页。
3. 下载了最新版的 hithesis.bst 文件，修正参考文献的标示空格bug，使参考文献的 DOI 信息不再另起一行，而是紧接在文献其他信息之后。
