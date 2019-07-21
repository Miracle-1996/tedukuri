﻿# tedukuri
tedukuri 是「手作り」的意思，读作「てづくり」(近似英文 tezukuli)，指的是由《算法竞赛进阶指南》的作者、读者一起，用自己的双手共同维护的资源社区。为此，我们选择了 GitHub 这个世界上最大的 Programmer Community 作为支持平台。

## Contents
目前，这个repo里包含以下内容：
- 第一版（2018年1月第一次印刷）最新勘误（更新于2018年6月5日）
- 第二版（2018年6月印刷）最新勘误（更新于2018年11月26日）
- 第三版（2018年11月印刷）最新勘误（更新于2018年11月26日）
- 包含本书专用题库、最新题目提交地址和标程、数据配备情况的附录表格
- 最新配套内容（随时更新习题翻译、标程、测试数据、习题题解等）

相比原书第一版配套光盘，这个repo已经先后多次增加了数十道POJ题目和BZOJ题目的测试数据，以及OJ未收录题目的测试数据，请参照提交历史(commits)或者最新的附录PDF。

## Instructions
#### 如何下载 GitHub 上的资源？
1. 可以直接点击页面上的绿色按钮"Clone or download"，下载整个zip压缩包（由于你懂的原因，速度可能会比较慢）。
2. 也可以在本地安装Git命令行或图形界面客户端，git clone(克隆)项目仓库，以后每次执行git pull都可以快速地增量更新。
3. 还可以找到想要的文件，直接右键另存为（只能保存单个文件，不能保存文件夹，数据文件较多时会比较麻烦）。
#### 如何做书中“OJ未收录”或“来源于非主流OJ”的题目？
可以访问Contest Hunter上的[本书专用题库](http://contest-hunter.org:83/contest?type=1)，这里对书中大部分例题、习题均有收录，并公开测试数据和所有用户提交的代码。另外[AcWing](https://www.acwing.com/problem/search/1/?csrfmiddlewaretoken=5es0vcpy4xlqy4BgN1NrRvM2v71SA5MFBx3FxI4fCZaxQYjX2lpKSNmRPfEJmtHs&search_content=%E7%AE%97%E6%B3%95%E7%AB%9E%E8%B5%9B%E8%BF%9B%E9%98%B6%E6%8C%87%E5%8D%97)也翻译并收录了本书全部题目。
#### 如何做BZOJ隐藏题目？
不熟悉的读者可能觉得书上的部分题目在BZOJ上找不到，这是因为BZOJ隐藏了部分题目（又称为权限题），只对收费的VIP用户开放。
1. 可以联系BZOJ管理员，购买2年VIP服务，价格在几百元左右，到了NOI阶段BZOJ上的题目有很高的价值。
2. 你也可以访问CH上的[本书专用题库](http://contest-hunter.org:83/contest?type=1)，直接免费做到这些题目中的绝大部分（原本是国内外公开比赛的题目）。
#### POJ突然挂了怎么办？
可以去OpenJudge上的[百练](http://bailian.openjudge.cn)题库搜索一下题目标题，OpenJudge也是北大运营的，题目与POJ有很大重合。
另外，[本书专用题库](http://contest-hunter.org:83/contest?type=1)已经实现了对OpenJudge的远端评测 (Virtual Judge)，也可以直接提交。
#### 为什么选用了很多老牌OJ的英文题目，英文捉鸡怎么办呢？
1. 即使是国内正规的比赛、最近新兴的OJ上（Luogu, CodeVS, LibreOJ等）的题目，很多也是翻译、借鉴自国外的idea。对于同种idea的题目，出于尊重原创者的考虑，我们一般会以最早的来源为标准。
2. 提高英文水平（至少到能看懂题面的程度）对于日后阅读科学文献和PKU/THU的选拔都很有帮助，很快你就会习惯了，不会耽误你的时间。
3. 实在是觉得费劲的话，可以Google/Bing一下"POJXXXX"或题目标题等关键字，搜索引擎可能会给出别人总结的题意，甚至是在其他中文OJ上的翻译版本噢！不过缺点是你可能会不小心搜到题目的解法。

## Contributions
除作者不断收集外，当读者获得数据或自己生成了数据，或者认为自己的解法独具一格、代码很具有参考价值时，非常欢迎为这个repo作出贡献。您的用户名将会永远地记录在提交历史 (commits) 中，并展示在 contributors 页面。您将对自己的改动负责，因此请确保其没有版权问题。

作为一名程序员，学习使用 Git 是一项基本生存技能。下面的步骤是给不熟悉 Git 相关流程的读者阅读的：
- 注册 GitHub 账户，并 `fork` 这个repo的最新副本到自己的账户下。
- `clone` 该副本到本地计算机，并创建一个新的分支 (branch)。
- 作出改动，在自己的分支上提交 (commit)，并写上一句简短、恰当的改动说明。
- 打开一个 `Pull Request`，请求合并改动到原repo，等待审核通过或得到修改意见。

更详细的指南请参考 [Git 手册](https://git-scm.com/book/zh/v2/GitHub-%E5%AF%B9%E9%A1%B9%E7%9B%AE%E5%81%9A%E5%87%BA%E8%B4%A1%E7%8C%AE)。您可能需要安装软件来获得 Git 命令行或图形化界面工具。
