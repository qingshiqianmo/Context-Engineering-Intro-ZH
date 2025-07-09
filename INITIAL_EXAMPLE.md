## 功能：

- Pydantic AI 代理，其中有另一个 Pydantic AI 代理作为工具。
- 主代理的研究代理，然后子代理的电子邮件草稿代理。
- 用于与代理交互的 CLI。
- 电子邮件草稿代理使用 Gmail，研究代理使用 Brave API。

## 示例：

在 `examples/` 文件夹中，有一个 README 供您阅读，以了解示例的全部内容，以及在为上述功能创建文档时如何构建自己的 README。

- `examples/cli.py` - 使用此作为模板来创建 CLI
- `examples/agent/` - 阅读此处的所有文件，了解创建支持不同提供商和 LLM 的 Pydantic AI 代理、处理代理依赖项以及向代理添加工具的最佳实践。

不要直接复制这些示例，它们是为完全不同的项目准备的。但是将其用作灵感和最佳实践。

## 文档：

Pydantic AI 文档：https://ai.pydantic.dev/

## 其他考虑：

- 包括 .env.example、带有设置说明的 README，包括如何配置 Gmail 和 Brave。
- 在 README 中包含项目结构。
- 虚拟环境已经设置了必要的依赖项。
- 使用 python_dotenv 和 load_env() 处理环境变量