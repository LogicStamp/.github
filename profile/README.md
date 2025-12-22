## LogicStamp

### AI-ready context for modern React/TypeScript codebases  
Structured snapshots for accurate, reliable LLM-assisted development.

<div align="center">
  <img src="https://logicstamp.dev/mascot/logicstamp-fox.svg" width="120" alt="LogicStamp Fox Mascot" />

  <br/>

  <a href="https://logicstamp.dev">Website</a>
  ·
  <a href="https://logicstamp.dev/docs">Docs</a>
  ·
  <a href="https://github.com/LogicStamp/logicstamp-context">CLI</a>
  ·
  <a href="https://github.com/LogicStamp/logicstamp-mcp">MCP</a>
</div>

---

## What is LogicStamp?

LogicStamp is an open-source toolkit that converts React/TypeScript codebases into **structured, AI-ready context bundles** — enabling dramatically more accurate LLM-assisted development.

No more invented files.  
No more missing props.  
No more architecture-breaking hallucinations.

Used today by real developers in production-scale React/Next.js projects.

---

## Projects

### **logicstamp-context (CLI)**
Generates component contracts, dependencies, props, routes, styles, and metadata for LLMs.  
➡️ https://github.com/LogicStamp/logicstamp-context

### **logicstamp-mcp (Model Context Protocol Server)**  
Bring LogicStamp into Claude, Cursor, Windsurf, and AI IDEs via MCP.  
➡️ https://github.com/LogicStamp/logicstamp-mcp  

### **logicstamp.dev (Docs & Landing Page)**  
Official documentation, guides, examples, and onboarding.  
➡️ https://github.com/LogicStamp/logicstamp.dev

---

## Why LogicStamp?

- Eliminates guesswork in large React/Next.js codebases  
- Prevents hallucinated components and broken refactors  
- Produces **machine-readable snapshots** optimized for LLMs  
- Designed for MCP, AI coding assistants, and modern AI workflows  
- Helps LLMs understand your architecture the way *you* do  

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

Start the MCP server:

```bash
npx logicstamp-mcp
```

## Then tell your AI assistant to use the LogicStamp MCP Server to analyze your project.

---

## Contributing
Issues and PRs are welcome across all repositories.

## Contact
logicstamp.dev@gmail.com
