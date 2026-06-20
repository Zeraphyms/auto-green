# 自动提交
🌳 可以让你的贡献图变绿，由[Github Actions](https://github.com/features/actions)驱动

![Zeraphyms's Github Stats](https://ghchart.rshah.org/Zeraphyms)
## 创建你自己的仓库
通过点击"**Use this template**"创建你自己的仓库（⚠️不要Fork本仓库，Fork项目的动态不会让你的贡献图变绿）

创建后，你需要配置你自己的仓库，前往：**Settings** -> **Action** -> **General** -> **Workflow permissions** 选择 **"Read and write permissions"**
- 配置你的`email`和`name`，在文件[autocommit.yml, line 31 and 32](https://github.com/Zeraphyms/auto-green/blob/main/.github/workflows/autocommit.yml#L31L32) .
- *你也可以调整（非必要）[autocommit.yml, line 9](https://github.com/Zeraphyms/auto-green/blob/main/.github/workflows/autocommit.yml#L9) ，修改想要自动执行的时间（注：此时间为UTC+0的时区，且会因为Github Actions服务器拥堵和排队，大概率不能够准时分执行），时间格式可以参考[crontab.guru](https://crontab.guru/) 。
- 如果喜欢本项目，可以给[我的💩](https://github.com/Zeraphyms/auto-green)点一个🌟Star.
---
© 2026 Crafted by Zeraphyms
