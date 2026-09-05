# AWS Agentic AI Workshop

Hands-on implementation of agentic AI systems on AWS, covering both self-managed and AWS-managed GenAI infrastructure.

## What I Built

This repository contains two implementations of an AI-powered customer service agent:

### Self-Managed GenAI

Built and deployed agentic AI components on Amazon EKS using:

- Strands Agents
- LiteLLM
- Langfuse observability
- Milvus vector database
- RAG (Retrieval-Augmented Generation)
- Conversational memory
- MCP (Model Context Protocol)
- Multi-Agent A2A communication
- Neo4j Knowledge Graph
- LLM-as-a-Judge evaluation

### Integrated GenAI

Rebuilt the agent using AWS managed GenAI capabilities:

- Amazon Bedrock / Nova
- Amazon Bedrock AgentCore Memory
- AgentCore Code Interpreter
- AgentCore Browser
- Langfuse observability
- Multi-Agent A2A architecture
- AgentCore Evaluations
- Custom and built-in LLM-as-a-Judge evaluators

## Repository Structure

```text
aws-agentic-ai-workshop/
├── self-managed/
│   ├── 200-strands-agents/
│   ├── 300-observability-langfuse/
│   ├── 400-rag-milvus/
│   ├── 500-memory-milvus/
│   ├── 600-agent-tools-mcp/
│   ├── 700-multi-agent-a2a/
│   └── 800-knowledge-graph/
│
└── integrated/
    ├── 100-strands-bedrock/
    ├── 200-observability-langfuse/
    ├── 300-memory-agentcore/
    ├── 400-managed-tools/
    ├── 500-multi-agent-a2a/
    └── 550-evaluation-agentcore/
