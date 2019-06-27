# bibs使用说明

## 1、使用此bibliography的方法

使用Latex+Bibtex+Jabref在论文中插入参考文献，具体方法可百度。

## 2、网络至本地bib文件同步的方法

首次：使用Github Desktop软件 File==> Clone Repository ==> Fetch origin.

其他：使用Github Desktop软件 ==> 选择Current repository 为 bibs ==> Fetch origin.


## 3、本地文件至网络的同步方法

### 如果本地有另一个A.bib文件，可使用如下方法：
使用Jabref打开bib.bib文件 ==> File ==> Import to current library ==> Select file (A.bib) ==> Deselect all duplicates ==> OK.
继续进行第（2）步。

### 如果本地直接使用bib.bib 文件，在文件中新增了文献的条目，则
使用Github软件 ==> 选择Current repository 为 bibs ==> 在左下角填写 Summary、Description ==> Commit to master ==> Push origin.

## 4、BibTex Key的生成

（1）建议使用Auto Generate Key功能： Jabref ==> Options ==> Preferences ==> BibTex Key generator ==> Default pattern 中输入 *[auth][year]*

（2）在Quality中，选择AutoGenerate BibTex Key
