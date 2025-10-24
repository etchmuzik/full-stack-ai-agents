# Full-Stack AI Agents for Coding

This repository contains a conceptual setup for a “full‑stack” team of AI agents that can help with coding tasks, bug fixing, code review, and retrieval‑augmented generation (RAG) workflows.  The stack combines Anthropic’s **Claude Code** with **Visual Studio Code** and OpenAI’s **ChatGPT**.

## Components

- **Claude Code** – a coding agent that can explore your codebase, modify files, run terminal commands and suggest changes directly in your editor.  To integrate it with VS Code, install the official extension or run `claude` in your integrated terminal and use the `/ide` command to connect.
- **ChatGPT** – a conversational assistant that can explain code, brainstorm ideas, and help with general questions.  Install the “Work with Apps” extension or a ChatGPT extension in VS Code to access ChatGPT models within your editor.
- **RAG Layer (optional)** – for advanced use‑cases, set up a retrieval‑augmented generation pipeline using LangChain or another framework.  This indexes your codebase and documentation and provides context to your agents.

## Usage

1. **Install Claude Code**:
   - Run `claude` in your integrated terminal.  In the prompt, use `/ide` to connect to VS Code.
   - Alternatively, install the Claude Code extension from the Visual Studio Marketplace.
2. **Install ChatGPT**:
   - Download the `openai-chatgpt.vsix` file from OpenAI.
   - Open the Command Palette in VS Code and choose “Extensions: Install from VSIX…” to install.
   - Sign in with your OpenAI account.
3. **(Optional) Configure RAG**:
   - Use a framework like LangChain to build a vector index of your codebase.
   - Connect your agents to the index so they can retrieve relevant context when generating or reviewing code.

## Disclaimer

This repository does not contain runnable code; rather, it outlines the steps required to set up a multi‑agent coding environment.  You will need valid subscriptions for Claude Code and ChatGPT to use them within VS Code.
