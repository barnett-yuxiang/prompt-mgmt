
### working with context

两种类型的上下文

- Intent Context：用户希望从模型中获得什么？| what you want?
- State Context：错误信息，控制台日志，图片和代码片段，状态相关的上下文示例 | what's true

两种上下文协同，使 curzor 提供有用的代码建议。

Cursor 核心设计具备上下文感知能力，尽可能减少用户的干预。

**@-symbol**：提供显示上下文，code，file，folder

**Rules**：
