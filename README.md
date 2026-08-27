# AI Agents: comportamento, multi-agentes e A2A

Apresentação de 1 hora para aprofundamento conceitual sobre agentes: o que caracteriza agência, como agentes percebem/representam/decidem/agem, como diferentes arquiteturas produzem comportamentos distintos e como isso escala para colaboração multi-agent.

A apresentação mantém exatamente os slides 6 a 11 da versão `master` do repositório original via `reference.html`. O restante do deck foi reorganizado em torno desse bloco fixo para manter a narrativa coerente.

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

## Estrutura final dos slides

### Parte 01 — Fundamentos de agência
- **Slide 01:** AI Agents — capa e framing da aula.
- **Slide 02:** Estrutura da aula — três partes e fio condutor.
- **Slide 03:** O que torna algo um agente? — automação × workflow dinâmico × agente.
- **Slide 04:** Agente, ambiente e loop — observation, state, goal, action e feedback loop.
- **Slide 05:** Comportamentos de agentes — reactive, model-based, goal-directed, deliberative e planning/replanning.

### Parte 02 — Multi-Agent & A2A preservados
- **Slides 06 a 11:** preservados exatamente da branch `master`, cobrindo limites de um agente único, problema de comunicação, introdução ao A2A, primitivas e caso do assistente de viagem.

### Parte 03 — Sistemas agentic em operação
- **Slide 12:** divisor visual da Parte 03.
- **Slide 13:** Coordination patterns — supervisor, handoff e collaborative.
- **Slide 14:** Dynamic workflows — static, conditional, dynamic e workflow patterns.
- **Slide 15:** Production reality — bounded autonomy, permissions, retries, timeouts, idempotency e observability.
- **Slide 16:** Modelo mental final — síntese do loop agentic.

---

## Observações de design

- Slides editáveis seguem o estilo editorial do deck original: fundo claro/azul/preto, tipografia Inter, azul `#350EFF`, cards amplos, diagramas visuais e baixa densidade textual.
- Slides 6–11 não devem ser alterados diretamente; qualquer ajuste neles deve ser feito apenas se a exigência de preservação for removida.
