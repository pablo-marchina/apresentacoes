# AI Agents: comportamento, multi-agentes e A2A

Apresentação de 1 hora para aprofundamento teórico em agentes: o que caracteriza agência, como um agente observa/representa/decide/age, como diferentes arquiteturas geram comportamentos distintos e como sistemas multi-agent se comunicam.

A apresentação mantém exatamente os slides 6 a 11 da versão `master` do repositório original. Esses slides são carregados a partir de `reference.html`, preservando o bloco de Multi-Agents e A2A sem alterações, enquanto o restante do deck foi reorganizado ao redor da estrutura teórica definida.

---

## Como visualizar

Use um servidor local para garantir o carregamento de `reference.html`:

```bash
python3 -m http.server 3000
```

Acesse:

```text
http://localhost:3000
```

---

## Estrutura dos slides

### Parte 1 — Fundamentos de agência
- **Slide 01:** AI Agents — capa e framing da aula.
- **Slide 02:** Estrutura da aula — roteiro de 60 minutos.
- **Slide 03:** O que torna algo um agente? — pergunta central.
- **Slide 04:** Agente, ambiente e loop — observation, state, goal e action.
- **Slide 05:** Comportamento e autonomia — reactive, model-based, goal-based, utility, planning/replanning e decomposição.

### Parte 2 — Multi-Agents e A2A preservados
- **Slides 06 a 11:** preservados exatamente da branch `master`, cobrindo limites de um agente único, problema de comunicação, introdução ao A2A, primitivas e caso do assistente de viagem.

### Parte 3 — Diferenciais técnicos
- **Slide 12:** Workflows dinâmicos & produção — transição para controle de fluxo.
- **Slide 13:** Workflow patterns — sequential, routing, parallel/fan-in e orchestrator-workers.
- **Slide 14:** Protocolos de comunicação — intenções, contratos e mensagens estruturadas.
- **Slide 15:** Production scenarios — customer support, software engineering e operations.
- **Slide 16:** Modelo mental final — síntese da aula.

---

## Atalhos

| Ação | Teclas |
| :--- | :--- |
| Próximo slide | `→`, `Espaço`, `Enter`, `Page Down` |
| Slide anterior | `←`, `Backspace`, `Page Up` |
| Primeiro / último slide | `Home` / `End` |
| Tela cheia | `F` |
| Visão geral | `O` ou `G` |
| Exportar para PDF | botão `PDF` ou `Ctrl + P` |
