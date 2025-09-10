[![CodeQL Advanced](https://github.com/japoch/ai-models/actions/workflows/codeql.yml/badge.svg)](https://github.com/japoch/ai-models/actions/workflows/codeql.yml)
[![Codacy Security Scan](https://github.com/japoch/ai-models/actions/workflows/codacy.yml/badge.svg)](https://github.com/japoch/ai-models/actions/workflows/codacy.yml)
[![Automatic Dependency Submission](https://github.com/japoch/ai-models/actions/workflows/dependency-graph/auto-submission/badge.svg)](https://github.com/japoch/ai-models/actions/workflows/dependency-graph/auto-submission)

# AI Models
Evaluating GitHub AI models.

## Running locally
- Install [AI Toolkit for Visual Studion Code](https://marketplace.visualstudio.com/items?itemName=ms-windows-ai-studio.windows-ai-studio)
- Choose a model with low hardware requirements, e.g. [Phi 4 Mini](https://huggingface.co/microsoft/Phi-4-mini-instruct-onnx)
- Test your model in the playground and create sample code

## Running remotely
Set your access token with export GITHUB_TOKEN="<your-github-token-goes-here>".

GitHub with Free access with [simple rate limits](https://docs.github.com/github-models/prototyping-with-ai-models#rate-limits). Enable billing for higher limits with paid models usage.
Create Personal Access Token with models:read permissions.

## AI Platforms
The [Open Neural Network Exchange (ONNX)](https://onnx.ai/) is an open-source artificial intelligence ecosystem of technology companies and research organizations that establish open standards for representing machine learning algorithms and software tools to promote innovation and collaboration in the AI sector. ONNX is available on GitHub.

[Ollama](https://ollama.com/) is an advanced AI platform that brings large language models directly to your device. With its privacy-first approach and high-speed processing, Ollama enables seamless AI interactions without cloud dependencies. Whether you're coding, automating tasks, or engaging in deep conversations, Ollama provides a reliable and customizable AI experience. Ollama is available on GitHub.

## SDKs
Azure AI Inference SDK [documentation](https://aka.ms/azsdk/azure-ai-inference/python/reference) and [samples](https://aka.ms/azsdk/azure-ai-inference/python/samples).

OpenAI SDK [documentation](https://platform.openai.com/docs/overview?lang=python) and [samples](https://cookbook.openai.com/).
