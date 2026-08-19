### working with context

两种类型的上下文

- Intent Context：用户希望从模型中获得什么？| what you want?
- State Context：错误信息，控制台日志，图片和代码片段，状态相关的上下文示例 | what's true

两种上下文协同，使 curzor 提供有用的代码建议。

Cursor 核心设计具备上下文感知能力，尽可能减少用户的干预。

**@-symbol**
提供显示上下文，code，file，folder

**Rules**
视为一种长期记忆
也可以从现有对话中生成规则。如果有一段较长的对话来回进行了大量提示，那么很可能包含有用的指导方针或通用规则，可能希望再次使用他们。

**MCP**
MCP 是一个扩展层
开发环境，可能希望使用不同类型的服务器。比如内部文档，项目管理 Linear，Jira

