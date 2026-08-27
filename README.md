# AI Agents: comportamento, multi-agentes e A2A

Apresentação de 1 hora para aprofundamento conceitual em agentes: o que caracteriza agência, como um agente observa/representa/decide/age, por que arquiteturas diferentes geram comportamentos distintos e como isso escala para colaboração multi-agent.

A apresentação mantém exatamente os slides 6 a 11 da versão `master` do repositório original. Esses slides são carregados a partir de `reference.html`, preservando o bloco de Multi-Agents e A2A sem alterações, enquanto o restante do deck foi reorganizado ao redor da estrutura equilibrada definida para a aula.

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

### Parte 1 — Fundamentos e comportamento agentic
- **Slide 01:** AI Agents — capa e framing da aula.
- **Slide 02:** Estrutura da aula — roteiro de 60 minutos e fio condutor: perceber, representar, decidir e agir.
- **Slide 03:** O que torna algo um agente? — diferença entre automação, workflow dinâmico e agente.
- **Slide 04:** Agente, ambiente e loop — observation, state, goal, action e feedback do ambiente.
- **Slide 05:** Comportamentos de agentes — reactive, model-based, goal-directed, deliberative, planning/replanning e ponte para multi-agent.

### Parte 2 — Multi-Agents e A2A preservados
- **Slides 06 a 11:** preservados exatamente da branch `master`, cobrindo limites de um agente único, problema de comunicação, entrada no A2A, primitivas do protocolo e caso do assistente de viagem.

### Parte 3 — Sistemas agentic na prática
- **Slide 12:** Coordenação — divisor após o exemplo A2A.
- **Slide 13:** Coordination patterns — supervisor, handoff e collaborative.
- **Slide 14:** Dynamic workflows — static, conditional, dynamic e principais workflow patterns.
- **Slide 15:** Production reality — persistence, retries, timeouts, idempotency, permissions, observability e human approval.
- **Slide 16:** Modelo mental final — síntese visual do agent loop e dos comportamentos discutidos.

---

## Foco da aula

O foco não é ensinar frameworks nem transformar A2A no tema principal. O foco é construir um modelo mental sólido sobre agentes:

```text
Agent → Environment → Loop → State/Goals/Actions → Behaviors → Reactive/Deliberative → Planning/Replanning → Multi-Agent/A2A → Coordination → Dynamic Workflows → Production → Synthesis
```

A2A, workflow patterns e production scenarios entram como aplicações e diferenciais, não como o centro da aula.
