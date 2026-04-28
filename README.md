# Agent Craft

Um agente que cria outros agentes.

O Agent Craft transforma uma necessidade descrita em linguagem natural em um agente completo e funcional, com 8 seções obrigatórias, pronto para ser colado nas instructions de um Project no Claude.ai.

---

## O que é

O Agent Craft é um agente de IA construído para o Claude.ai. Ele não produz prompts genéricos — produz agentes com identidade, filosofia, protocolo de colaboração e estrutura de output definidos.

Desenvolvido a partir da prática de construir sistemas multi-agente no projeto Foundi.

---

## Como usar

### 1. Crie um Project no Claude.ai
Acesse [claude.ai](https://claude.ai) e crie um novo Project.

### 2. Cole as instructions
Abra as configurações do Project, vá em **Instructions** e cole o conteúdo do arquivo `agent-craft-instructions.md`.

### 3. Descreva o que você precisa
Abra um chat dentro do Project e descreva em linguagem natural o agente que você quer criar. Exemplo:

> "Quero um agente que me ajude a preparar entrevistas de emprego em inglês."

### 4. Responda as perguntas
O Agent Craft vai fazer no máximo 3 perguntas para entender o contexto antes de escrever.

### 5. Copie o resultado
O agente gerado vem com as 8 seções prontas para colar. Crie um novo Project, cole nas instructions e seu agente está pronto.

---

## Estrutura do repositório

```
agent-craft/
├── README.md                        ← este arquivo
└── agent-craft-instructions.md      ← instructions para colar no Claude.ai
```

---

## As 8 seções de um agente

Todo agente gerado pelo Agent Craft segue essa estrutura:

| # | Seção | O que define |
|---|-------|-------------|
| 1 | Identidade | Quem é o agente, papel e propósito |
| 2 | Contexto | Quem é o usuário, o que faz e o que não faz |
| 3 | Filosofia | Princípios que guiam as decisões |
| 4 | Framework de decisão | Critérios antes de responder |
| 5 | Processo | Como executa o trabalho |
| 6 | Comunicação | Tom, formato e template de output |
| 7 | Colaboração | Peer collaboration protocol |
| 8 | Gestão do fluxo | Ordem de operações e condições de desvio |

Tira uma, o agente perde coerência.

---

## Créditos

Estrutura de 8 seções desenvolvida por Thiago Almeida.

---

*Português do Brasil por padrão. O agente produzido pode estar em qualquer idioma.*
