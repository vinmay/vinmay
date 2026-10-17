Hey, I'm Vinmay.

Senior engineer with 10+ years in distributed systems and backend platforms (Java, Scala, Python).

Outside work I'm digging into how small models actually work, what AI agents
can really do, and where developer tooling falls short. I like building things
from scratch and figuring out why they don't behave the way I expected.

### Things I've built

- **[reachscan](https://github.com/vinmay/reachscan)**: Static analysis CLI that
  shows what an AI agent or MCP server can read, write, execute, or send, and
  whether an LLM can reach it. 0.47% false-positive rate.
  `pipx install reachscan` · [What I found scanning 50 MCP servers](https://medium.com/@vinmayN/i-scanned-50-mcp-servers-to-see-what-they-can-actually-do-46144659ceca)
- **[doppel](https://github.com/vinmay/doppel)**: On-device semantic scavenger
  hunt using EmbeddingGemma. Runs fully in the browser. [Live demo](URL)
- **[ratchet](https://github.com/vinmay/ratchet)**: Building a language model
  from scratch in NumPy: autograd, layers, attention, transformer. No ML
  framework. *In progress.*

### Writing

- [I scanned 50 MCP servers to see what they can actually do](https://medium.com/@vinmayN/i-scanned-50-mcp-servers-to-see-what-they-can-actually-do-46144659ceca):
  1 in 3 can run shell commands, 8 pair credential access with network egress,
  and one passes LLM input straight to `exec()`.
- [I built "npm audit" for AI agents](https://dev.to/vinmay/i-built-npm-audit-for-ai-agents-5fc8):
  Why I built reachscan and how it decides whether an LLM can actually trigger
  a dangerous capability.
- [Your `pip install` just stole your SSH keys](https://dev.to/vinmay/your-pip-install-just-stole-your-ssh-keys-the-litellm-supply-chain-attack-explained-4l52):
  How a malicious LiteLLM release used a `.pth` file to exfiltrate credentials
  on every Python startup, and what to do about it.

[LinkedIn](https://www.linkedin.com/in/vinmaynair/) · [X](https://x.com/vinmaynair)
