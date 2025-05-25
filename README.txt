
PASSO A PASSO DEPLOY N8N RENDER:

1. Crie um repositório no GitHub e suba esses arquivos.
2. No Render, clique em "New Web Service".
3. Selecione o repositório.
4. Configure:
   - Language: Node
   - Build Command: npm install && npm run build
   - Start Command: n8n
5. Configure as Environment Variables usando .env.example como base.
6. Clique em Deploy.

Login no N8N: Use N8N_BASIC_AUTH_USER e N8N_BASIC_AUTH_PASSWORD.
Acesse sua URL: https://connect7-n8n.onrender.com
