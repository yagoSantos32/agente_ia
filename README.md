Agente de Automação
O agente descrito neste repositório é um consultor inteligente de projetos digitais integrado ao WhatsApp e ao Notion. Ele foi projetado para transformar conversas informais em documentação organizada e planos de desenvolvimento estruturados. A automação ignora a primeira mensagem do usuário, mas registra todas as subsequentes no Notion como requisitos do projeto. A partir desses requisitos, o agente utiliza inteligência artificial para gerar um plano detalhado com etapas de criação, tecnologias recomendadas, entregáveis e cronograma inicial, que também é salvo no Notion. Enquanto isso, mantém a interação fluida no WhatsApp, simulando digitação e respondendo em tempo real, garantindo que cada ideia do cliente seja capturada e convertida em ação. Em resumo, este agente conecta comunicação, organização e planejamento em um único fluxo automatizado.

Observação: o projeto não será continuado por enquanto, pois os requisitos para bots no WhatsApp mudaram.

---
🚀 Tutorial de Teste

Instale o n8n

Siga a documentação oficial: https://docs.n8n.io

Importe o fluxo

Salve o arquivo do fluxo como workflow.json.

No n8n, clique em Import Workflow e selecione o arquivo.

Configure credenciais

Adicione suas credenciais do Notion (Database ID e token).

Configure os endpoints do WAHA para envio e recebimento de mensagens.

Teste no WhatsApp

Envie uma mensagem para o número conectado.

A primeira mensagem será ignorada.

As próximas mensagens serão salvas no Notion e usadas para gerar um plano de desenvolvimento.

O bot continuará respondendo normalmente.
