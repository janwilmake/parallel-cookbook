# Parallel Cookbook

> [!WARNING]
> Work In Progress.

## Recipes

Coming soon!

## Choose Your Context

Depending on your question, please choose the contexts needed:

- Full Documentation [![](https://badge.forgithub.com/janwilmake/parallel-documentation?maxTokens=10000000&lines=false)](https://uithub.com/janwilmake/parallel-documentation?maxTokens=10000000&lines=false)
- Parallel API Specification [![](https://badge.forgithub.com/janwilmake/parallel-openapi/tree/main/openapi.yaml)](https://uithub.com/janwilmake/parallel-openapi?maxTokens=10000000&lines=false) [![](https://b.lmpify.com/Select_A_Context)](https://letmeprompt.com?q=https://parallel.oapis.org/%20%20give%20me%20urls:%20which%20files%20are%20relevant%20for%20...)
- Parallel Website and Blog [![](https://badge.forgithub.com/janwilmake/parallel-website?maxTokens=10000000&lines=false)](https://uithub.com/janwilmake/parallel-website?maxTokens=10000000&lines=false)
- Python SDK [![](https://badge.forgithub.com/parallel-web/parallel-sdk-python?maxTokens=10000000&lines=false)](https://uithub.com/parallel-web/parallel-sdk-python?maxTokens=10000000&lines=false)

Quickstart prompt:

```md
@https://docs.parallel.ai/llms.txt
@https://parallel.oapis.org/llms.txt
@https://uithub.com/janwilmake/parallel-website/tree/main?omitFiles=true (append filepath to this URL to get a specific file)

I want to build an app with [your-technology-stack]

Specification:
[your-spec]

Please give me the URLs as @{URL} that are relevant context for this task
```

<!--
- 🟠 Typescript SDK (https://uithub.com/parallel-web/parallel-sdk-typescript)
- 🟠 MCP server to select context (Coming soon!)
-->

How to use it?

- In Claude, Gemini, ChatGPT, or any other LLM of preference: Just copy-paste the context or use a GPT or MCP that can fetch URLs.
- [Cline @ Mentions](https://docs.cline.bot/features/at-mentions/overview)
- [Cursor @ Symbols](https://docs.cursor.com/en/context/@-symbols/overview)
- [Context Management in VSCode](https://code.visualstudio.com/docs/copilot/chat/copilot-chat-context#_add-files-as-context) works with URLs directly
- [Claude Code](https://www.anthropic.com/engineering/claude-code-best-practices) works with URLs directly
