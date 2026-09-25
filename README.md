# AI Agents Lab

My experiments with agentic AI frameworks, collected in one place: a managed AWS Bedrock flow, a low-code Langflow pipeline, and a progressive set of LangGraph examples written in Python.

| Folder | Framework | What it is |
|---|---|---|
| [`bedrock-quiz-agent/`](bedrock-quiz-agent/) | AWS Bedrock Flows + Agents | Cybersecurity quiz generator: a Bedrock Flow that routes a topic through a security-expert agent backed by AstraDB context |
| [`langflow-mcq-generator/`](langflow-mcq-generator/) | Langflow | No-code MCQ generator: Input → Astra DB → Parser → Prompt → Groq LLM, exported as a Langflow JSON |
| [`langgraph/`](langgraph/) | LangGraph | Step-by-step examples: [level 1](langgraph/level-1/) basic LLM calls, [level 2](langgraph/level-2/) conversation memory, [level 3](langgraph/level-3/) tool-calling agents, plus [misc](langgraph/misc/) experiments |

Each folder has its own README with setup steps and sample output.

## History

This repo merges three earlier repositories, now archived: [`bedrock_astra`](https://github.com/yashbhosale2403/bedrock_astra), [`langflow`](https://github.com/yashbhosale2403/langflow) and [`langgraph-eg`](https://github.com/yashbhosale2403/langgraph-eg).
