<div align="center">

<br>

# AIEvoDev

**AI-Powered Test Evolution**

Generate tests with GPT-4/Gemini, improve through adversarial mutation.

<br>

<a href="https://github.com/DeadManOfficial/AIEvoDev">
  <img src="https://img.shields.io/badge/GitHub-Source-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://www.python.org">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
</a>
<a href="https://langchain.com">
  <img src="https://img.shields.io/badge/LangChain-Powered-F39C12?style=for-the-badge" alt="LangChain" />
</a>

<br><br>

</div>

---

## How It Works

```
Generate → Evaluate → Evolve → Repeat
   │          │          │
   │     vs Correct     Improve
   │     vs Mutants     if better
   └──────────────────────┘
```

---

## Quick Start

```bash
git clone https://github.com/DeadManOfficial/AIEvoDev.git
cd AIEvoDev
pip install -e .

# Configure API key
cp .env.example .env

# Run
aievodev init
aievodev run specs/example_test_spec.yaml src/utils.py
```

---

## Features

| Feature | Description |
|---------|-------------|
| **Auto Generation** | Create test suites in minutes |
| **Evolution** | Tests improve each generation |
| **Mutation Testing** | Finds edge cases you'd miss |
| **Production Ready** | Outputs clean pytest code |

---

## Supported LLMs

| Provider | Models |
|----------|--------|
| OpenAI | gpt-4o-mini, gpt-4o, gpt-4-turbo |
| Google | gemini-2.0-flash, gemini-pro |

---

## Related

- **[mcp-auditor](https://github.com/DeadManOfficial/mcp-auditor)** — Security auditor for Claude
- **[token-optimization](https://github.com/DeadManOfficial/token-optimization)** — Save 30-50% on API costs
- **[DeadManIntelligenceCommand](https://github.com/DeadManOfficial/DeadManIntelligenceCommand)** — 5-agent intel platform

---

## License

MIT

---

<div align="center">

<br>

<a href="https://twitter.com/DeadManAI">
  <img src="https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white" alt="X" />
</a>
<a href="https://youtube.com/@DeadManAI">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white" alt="YouTube" />
</a>
<a href="https://tiktok.com/@DeadManAI">
  <img src="https://img.shields.io/badge/TikTok-000000?style=flat&logo=tiktok&logoColor=white" alt="TikTok" />
</a>

<br><br>

<sub>**BUILD > BUY**</sub>

</div>
