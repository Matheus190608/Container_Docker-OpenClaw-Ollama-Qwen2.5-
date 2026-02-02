# OpenClaw + Ollama Qwen2.5 Local (Zero Tools)

## 🚀 Setup Rápido (5min)

1. \`docker compose up -d ollama\`
2. \`docker exec ollama-qwen ollama pull qwen2.5:7b\`
3. Instalar OpenClaw: \`irm https://openclaw.ai/install.ps1 | iex\`
4. \`export OLLAMA_HOST="host.docker.internal:11434"\`
5. \`openclaw gateway\`

## 🌐 Acessar
http://127.0.0.1:18789

## ✅ Configs Atuais
- **Modelo**: qwen2.5:7b (4.68GB local)
- **Tools/Skills**: DISABLED 
- **Gateway**: porta 18789
