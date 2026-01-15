<br/>

<div align="center">
  <p align="center">
  <a href="https://logicstamp.dev">
    <img src="https://raw.githubusercontent.com/LogicStamp/logicstamp.dev/main/public/logicstamp-woodmark-no-bg.png"
         alt="LogicStamp"
         width="320" />
  </a>
</p>

<br/>

**AI-ready context bundles for modern React and TypeScript codebases.**
</div>

<div align="center">

  <a href="https://logicstamp.dev">Website</a>
  ·
  <a href="https://logicstamp.dev/docs">Docs</a>
  ·
  <a href="https://www.npmjs.com/~amitek">npm</a>
  ·
  <a href="https://github.com/LogicStamp/logicstamp-context">CLI</a>
  ·
  <a href="https://github.com/LogicStamp/logicstamp-mcp">MCP</a>
</div>

---

<p align="center">
  <img
    src="https://raw.githubusercontent.com/LogicStamp/logicstamp.dev/main/public/logicstamp-workflow.gif"
    alt="LogicStamp MCP analyzing a real React + Tailwind codebase"
    width="900"
  />
</p>

<p align="center">
  <em>
    LogicStamp MCP server building a structured, Tailwind-aware view of a React codebase.<br/>
    CLI-driven context bundles generated and consumed via MCP.
  </em>
</p>

---

## What is LogicStamp?

**LogicStamp** is an open-source developer toolkit for **context engineering**.

It statically analyzes React and TypeScript codebases and produces **deterministic, structured context bundles** that accurately model a codebase architecture - components, props, hooks, dependencies, styles, and contracts.

These bundles provide LLMs and developer tools with **ground-truth architectural context**, enabling reliable AI-assisted development across editors, CI, and agent workflows.

LogicStamp is designed to make AI systems understand your codebase - not guess at it.

---

## Why LogicStamp?

Large language models are powerful, but they depend entirely on the quality of the context they receive.  
LogicStamp bridges this gap by transforming source code into **machine-readable architectural context** that is precise, reproducible, and safe.

LogicStamp is:

- **Deterministic** - the same code produces the same context every time  
- **Static** - no runtime execution, no code mutation  
- **Framework-aware** - deep understanding of React and TypeScript semantics  
- **Composable** - usable via CLI, MCP, and downstream tooling  

---

## What does LogicStamp enable?

- Eliminates guesswork in large React and Next.js codebases  
- Prevents hallucinated components and architecture-breaking refactors  
- Produces **machine-readable architectural context** optimized for LLMs  
- Designed for MCP, AI coding assistants, and modern agent workflows  
- Helps LLMs understand your architecture the way you do  

---

## 📦 Install - CLI

```bash
npm install -g logicstamp-context
```

## Generate context (with style metadata)

```bash
stamp context style
```

## Generate context (without style)

```bash
stamp context
```

## 📡 Install - MCP Server

```bash
npm install -g logicstamp-mcp
```

Setup guide → https://logicstamp.dev/docs/mcp/getting-started

#### 👉 Then tell your AI assistant to use the LogicStamp MCP Server to analyze your project.

---

  <p align="center">
  <a href="https://logicstamp.dev">
    <img src="https://raw.githubusercontent.com/LogicStamp/logicstamp.dev/main/public/mascot/logicstamp-fox.svg"
         alt="LogicStamp"
         width="120" />
  </a>
</p>

## Contributing
Issues and PRs are welcome across all repositories.

## Community
This project follows a [Code of Conduct](https://logicstamp.dev/code-of-conduct). By participating, you agree to uphold it.
<br/>
👉 Join our [Roadmap](https://logicstamp.dev/roadmap) to stay updated!

## Contact
logicstamp.dev@gmail.com
