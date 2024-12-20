# Welcome to Eidolon - an Open Source Agent Service SDK
 
[![Tests - Status](https://img.shields.io/github/actions/workflow/status/eidolon-ai/eidolon/test_python.yml?style=flat&label=eidolon)](https://github.com/eidolon-ai/eidolon)
[![PyPI](https://img.shields.io/pypi/v/eidolon-ai-sdk?style=flat&label=eidolon-ai-sdk)](https://pypi.org/project/eidolon-ai-sdk/)
[![PyPI](https://img.shields.io/pypi/v/eidolon-ai-client?style=flat&label=eidolon-ai-client)](https://pypi.org/project/eidolon-ai-client/)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/eidolon-ai-sdk?color=blue)](https://pypistats.org/packages/eidolon-ai-sdk)
[![GitHub - Stars](https://img.shields.io/github/stars/eidolon-ai/eidolon?style=flat&color=blue)](https://github.com/eidolon-ai/eidolon)

| Status | [agent-machine](https://github.com/eidolon-ai/agent-machine) | [eidolon-quickstart](https://github.com/eidolon-ai/eidolon-quickstart) | [eidolon-s3-rag](https://github.com/eidolon-ai/eidolon-s3-rag) | [eidolon-git-search](https://github.com/eidolon-ai/eidolon-git-search) | [eidolon-chatbot](https://github.com/eidolon-ai/eidolon-chatbot) | [web-researcher](https://github.com/eidolon-ai/web-researcher) | [azure-llm](https://github.com/eidolon-ai/azure-llm) | [github-assistant](https://github.com/eidolon-ai/github-assistant) |
|--------|---------------|-------------------|----------------|-------------------|-----------------|----------------|-----------|------------------|
| Test | [![test](https://img.shields.io/github/actions/workflow/status/eidolon-ai/agent-machine/test.yml?label=test)](https://github.com/eidolon-ai/agent-machine/actions/workflows/test.yml) | [![test](https://img.shields.io/github/actions/workflow/status/eidolon-ai/eidolon-quickstart/test.yml?label=test)](https://github.com/eidolon-ai/eidolon-quickstart/actions/workflows/test.yml) | [![test](https://img.shields.io/github/actions/workflow/status/eidolon-ai/eidolon-s3-rag/test.yml?label=test)](https://github.com/eidolon-ai/eidolon-s3-rag/actions/workflows/test.yml) | [![test](https://img.shields.io/github/actions/workflow/status/eidolon-ai/eidolon-git-search/test.yml?label=test)](https://github.com/eidolon-ai/eidolon-git-search/actions/workflows/test.yml) | [![test](https://img.shields.io/github/actions/workflow/status/eidolon-ai/eidolon-chatbot/test.yml?label=test)](https://github.com/eidolon-ai/eidolon-chatbot/actions/workflows/test.yml) | [![test](https://img.shields.io/github/actions/workflow/status/eidolon-ai/web-researcher/test.yml?label=test)](https://github.com/eidolon-ai/web-researcher/actions/workflows/test.yml) | [![test](https://img.shields.io/github/actions/workflow/status/eidolon-ai/azure-llm/test.yml?label=test)](https://github.com/eidolon-ai/azure-llm/actions/workflows/test.yml) | [![test](https://img.shields.io/github/actions/workflow/status/eidolon-ai/github-assistant/test.yml?label=test)](https://github.com/eidolon-ai/github-assistant/actions/workflows/test.yml) |
| Sync | [![sync](https://img.shields.io/github/actions/workflow/status/eidolon-ai/agent-machine/update.yml?label=sync)](https://github.com/eidolon-ai/agent-machine/actions/workflows/update.yml) | [![sync](https://img.shields.io/github/actions/workflow/status/eidolon-ai/eidolon-quickstart/update.yml?label=sync)](https://github.com/eidolon-ai/eidolon-quickstart/actions/workflows/update.yml) | [![sync](https://img.shields.io/github/actions/workflow/status/eidolon-ai/eidolon-s3-rag/update.yml?label=sync)](https://github.com/eidolon-ai/eidolon-s3-rag/actions/workflows/update.yml) | [![sync](https://img.shields.io/github/actions/workflow/status/eidolon-ai/eidolon-git-search/update.yml?label=sync)](https://github.com/eidolon-ai/eidolon-git-search/actions/workflows/update.yml) | [![sync](https://img.shields.io/github/actions/workflow/status/eidolon-ai/eidolon-chatbot/update.yml?label=sync)](https://github.com/eidolon-ai/eidolon-chatbot/actions/workflows/update.yml) | [![sync](https://img.shields.io/github/actions/workflow/status/eidolon-ai/web-researcher/update.yml?label=sync)](https://github.com/eidolon-ai/web-researcher/actions/workflows/update.yml) | [![sync](https://img.shields.io/github/actions/workflow/status/eidolon-ai/azure-llm/update.yml?label=sync)](https://github.com/eidolon-ai/azure-llm/actions/workflows/update.yml) | [![sync](https://img.shields.io/github/actions/workflow/status/eidolon-ai/github-assistant/update.yml?label=sync)](https://github.com/eidolon-ai/github-assistant/actions/workflows/update.yml) |

Eidolon helps developers designing and deploying agent-based services.

## Why Eidolon?
### 1. Easy to deploy
With Eidolon, agents are services, so there is no extra work when it comes time to deploy. The HTTP server is built in.

### 2. Simple agent-to-agent communication
Since agents are services with well-defined interfaces, they easily communicate with tools dynamically generated from
the openapi json schema defined by the agent services.

### 3. Painless component customization and upgrade
With a focus on modularity, Eidolon makes it easy to swap out components. Grab an off the shelf llm, rag impl, tools,
etc or just define your own.

This means no vendor lock-in and minimizes the work needed to upgrade portions of an agent. Without this flexibility,
developers will not be able to adapt their agents to the rapidly changing AI landscape.

## Next Steps
⭐️ Star the [Source Code](https://github.com/eidolon-ai/eidolon)

🚀 Get started with the [Quickstart Guide](https://www.eidolonai.com/docs/quickstart)

🔎 Vist Eidolon's [Website](https://eidolonai.com/)


## Contributing

We welcome and appreciate contributions!

Reach out to us on [discord](https://discord.gg/6kVQrHpeqG) if you have
any questions or suggestions.

We maintain a list of [good first issues](https://github.com/orgs/eidolon-ai/projects/6/views/6) for new contributors. We try to make these issues self contained, but again, stop by discord with questions or ask them directly on the issue.

If you need help with the mechanics of contributing, check out the [First Contributions Repository](https://github.com/firstcontributions/first-contributions). 
