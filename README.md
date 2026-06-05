# LiweiCheng1203.github.io

我的学术主页，基于 [Academic Pages](https://github.com/academicpages/academicpages.github.io) 模板搭建。

🔗 **在线访问**: https://liweicheng1203.github.io

## 日常维护速查

| 想改什么 | 改哪个文件 |
|---|---|
| 姓名 / 机构 / 社交链接 | `_config.yml`（搜 `TODO`） |
| 首页自我介绍 | `_pages/about.md` |
| 头像 | 替换 `images/profile.png` |
| 添加论文 | 复制 `_publications/` 里已有条目改内容 |
| 添加报告 | 参考 `_example_formats/talk-example.md`，新文件放进 `_talks/`，并在 `_data/navigation.yml` 取消 Talks 注释 |
| 添加教学经历 | 参考 `_example_formats/teaching-example.md`，同上启用 Teaching 栏目 |
| CV 页面 | `_pages/cv.md` |
| 导航栏栏目 | `_data/navigation.yml`（注释里有恢复方法） |
| 上传 PDF | 放进 `files/`，访问 `/files/文件名.pdf` |

改完后 `git add . && git commit && git push`，1-3 分钟后自动生效。

## 批量导入论文

`markdown_generator/` 里有 Jupyter notebook，可以从 BibTeX（`PubsFromBib.ipynb`）或 TSV（`publications.ipynb`）批量生成论文页面。
