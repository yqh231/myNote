# myNote 项目指令

## 项目说明

这是一个个人学习笔记仓库，使用 Markdown 格式记录技术学习笔记。

## 图片管理规范

- 图片统一存放在 `images/` 目录下，按笔记主题创建子目录，例如 `images/rag/`
- 在 Markdown 中使用 GitHub 原始文件链接引用图片：
  ```
  ![描述](https://raw.githubusercontent.com/yqh231/myNote/main/images/主题/图片名.png)
  ```
- 如果引用外部开源项目的图片，优先下载到本地 `images/` 目录，避免外链失效
- 图片命名使用英文小写+连字符，如 `memory-architecture.png`

## 笔记编写规范

- 笔记使用中文编写，技术术语保留英文
- 文件名使用中文或英文均可，避免空格（用连字符代替）
- 每篇笔记开头应有简要说明和来源标注
- 使用标准 Markdown 语法，善用表格、代码块、引用等格式
- 不要在笔记中添加 emoji，除非用户明确要求