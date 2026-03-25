# aios-master @aios-master
---
description: Ativa o agente Aios-master
---

# Ativação do Agente Aios-master

**INSTRUÇÕES CRÍTICAS PARA O ANTIGRAVITY:**

1. Leia COMPLETAMENTE o arquivo `.antigravity/agents/aios-master.md`
2. Siga EXATAMENTE as `activation-instructions` definidas no bloco YAML do agente
3. Adote a persona conforme definido no agente
4. Execute a saudação conforme `greeting_levels` definido no agente
5. **MANTENHA esta persona até receber o comando `*exit`**
6. Responda aos comandos com prefixo `*` conforme definido no agente
7. Siga as regras globais do projeto em `.antigravity/rules.md`

**Comandos disponíveis:** Use `*help` para ver todos os comandos do agente.

---

# 🥋 FLUXO DE PROSPECÇÃO CORRETOR SAMURAI (MANDATÓRIO)
Sempre que o usuário solicitar a busca/análise de novos corretores imobiliários:

1. **BUSCA E IDENTIFICAÇÃO:** Realize a busca técnica (Perfil Independente, <5k seguidores, nicho Luxo ou MCMV).
2. **SETUP DO ARQUIVO:** Crie o arquivo individual `.md` e inclua obrigatoriamente no topo (links clicáveis):
   - **Instagram:** Perfil identificado na pesquisa.
   - **Site:** Link do site profissional/link-tree.
   - **WhatsApp:** Link direto `https://wa.me/55...`.
3. **ANÁLISE E MENSAGENS (UPDATE):** 
   - O usuário irá rodar manualmente o prompt `@file:Analise de Perfis para o Corretor Samurai` e inserir o resultado no arquivo.
   - Após esta inserção, a tarefa do assistente é apenas chamar o agent `@[intelligence/agents/dmcorretorsamurai.md]` para gerar (ou atualizar) as 3 DMs baseando-se no novo e completo contexto fornecido pela análise manual do usuário.
