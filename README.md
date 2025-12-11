# 《掌权的布尔什维克》整理本

此书是印地安那大学伯明顿分校荣休教授 Alexander Rabinowitch 著作 *The Bolsheviks in Power: The First Year of Soviet Rule in Petrograd* 的汉译版，译者为知乎用户[昌明林](https://www.zhihu.com/people/cml01)和 [lj soviet](https://www.zhihu.com/people/lj-soviet)，其中，昌明林翻译了原书的序言、引子以及第 15 章；lj soviet 翻译了原书的第 1 章至第 7 章。

已上传至 z-lib，另外，也可在 Github 阅读[最新版 pdf](./bolsheviks-in-power.pdf)。

## 技术细节
- 排版引擎：[Typst](https://typst.app)；
- 字体：
  - 汉文：[Noto Serif CJK SC](https://github.com/notofonts/noto-cjk)；
  - 西文：[Libertine](https://libertine-fonts.org)；

## 流程
1. 安装油猴脚本[知乎备份剪藏](https://github.com/qtqz/zhihu-backup-collect)，然后以 zip 格式下载文章；
2. 解压得到的 zip 文件，获得一些 markdown 文件以及图片；
3. 用 [Pandoc](https://pandoc.org) 把 markdown 转换为 typst；
4. 编译。
