# Design System — Slides de Referência

## 1. Direção visual

**Estética:** editorial, tecnológica, minimalista e premium, com linguagem visual de uma academy/startup de tecnologia.

**Sensação:** clareza + sofisticação + impacto. O conteúdo deve parecer uma apresentação de produto/tech, não um template corporativo tradicional.

**Princípios:**
- Muito espaço em branco.
- Poucos elementos por slide.
- Hierarquia tipográfica muito forte.
- Títulos grandes e curtos.
- Uma ideia principal por slide.
- Uso pontual de azul elétrico/roxo como cor de destaque.
- Diagramas e cards simples, sem efeitos 3D.
- Bordas finas e cantos arredondados.
- Evitar excesso de ícones, gradientes, sombras e ornamentos.

---

## 2. Formato da apresentação

- **Canvas:** 16:9
- **Resolução de referência:** 1920 × 1080
- **Orientação:** horizontal
- **Margens:** amplas, com conteúdo iniciando aproximadamente entre 6% e 7% da largura.
- **Grid:** preferencialmente baseado em 12 colunas.
- **Alinhamento principal:** esquerda.
- **Espaçamento vertical:** generoso; elementos não devem ficar "espremidos".

### Medidas de referência para 1920×1080

- Margem esquerda/direita: ~100 px.
- Topo de títulos: ~130–180 px, dependendo do tipo de slide.
- Área segura de conteúdo: ~1720 px de largura.
- Rodapés e etiquetas: pequenos e discretos.

---

## 3. Paleta de cores

### Cores principais

| Nome | HEX | Uso |
|---|---|---|
| Electric Blue / Purple | `#350EFF` | Cor principal de destaque, títulos de seção e elementos ativos |
| Deep Black | `#0A0A14` | Slides de abertura/separadores |
| White | `#FFFFFF` | Texto sobre fundos escuros e cards |
| Off White | `#F5F5F7` | Fundo principal dos slides de conteúdo |
| Graphite | `#272727` | Texto principal |
| Gray | `#5D5D66` | Texto secundário |
| Soft Gray | `#E6E6EC` | Linhas, bordas e divisores |
| Lavender Tint | `#EEEDF8` | Faixas/blocos de apoio |

### Cores de apoio

- Azul principal pode ser usado em pequenas áreas de preenchimento.
- Em slides escuros, o azul deve funcionar como elemento gráfico e o branco como tipografia.
- Não utilizar uma paleta grande. A apresentação deve parecer praticamente monocromática com um único acento forte.

---

## 4. Tipografia

### Característica

A tipografia é **sans-serif, moderna, geométrica e pesada nos títulos**.

Prioridade de fontes:

1. Inter
2. Helvetica Neue
3. Arial
4. Aptos / similar sans-serif, caso necessário

### Hierarquia

#### Eyebrow / Label
- Caixa alta.
- 16–22 px.
- Peso: Medium/Semibold.
- Tracking levemente aumentado.
- Cor: azul principal ou cinza.

Exemplo:

`PONTO DE PARTIDA`

#### Título principal
- 64–92 px.
- Peso: Bold/ExtraBold.
- Line-height: ~0.95–1.05.
- Muito contraste com o conteúdo secundário.
- Títulos podem ocupar várias linhas.

Exemplo:

`O que um LLM realmente sabe`

#### Título de capa
- 90–120 px.
- ExtraBold.
- Branco em fundo azul/roxo.
- Pode ocupar grande parte da largura.

Exemplo:

`RAG & Reranking`

#### Subtítulo
- 28–42 px.
- Peso Regular/Medium.
- Line-height de ~1.2–1.35.
- Cor: cinza ou branco, dependendo do fundo.

#### Corpo
- 22–30 px.
- Line-height confortável.
- Nunca usar blocos enormes de texto.

#### Texto pequeno / metadados
- 16–20 px.
- Cor cinza.
- Utilizado para labels, categorias e explicações curtas.

---

## 5. Slide de capa

### Estrutura

Fundo totalmente preenchido pelo **Electric Blue**.

No canto superior esquerdo:

`Inteli Academy`

Abaixo:

`FUNDAMENTOS DE IA APLICADA`

Título enorme:

`RAG & Reranking`

Subtítulo:

`Como dar memória, contexto e precisão a um modelo de linguagem.`

### Elemento gráfico

Usar uma composição abstrata de linhas geométricas finas, grandes e parcialmente cortadas pelas bordas.

Características:
- traço fino;
- azul claro/lavanda;
- baixa opacidade;
- formas angulares;
- ocupação principalmente no lado direito;
- não competir com o título.

### Regra

A capa deve parecer **ousada**, porém extremamente simples.

---

## 6. Slides de conteúdo

### Fundo

`#F5F5F7`

### Cabeçalho

No topo:
- eyebrow em azul;
- título grande em preto.

Exemplo:

`PONTO DE PARTIDA`

`O que um LLM realmente sabe`

### Conteúdo

Abaixo do título:
- cards;
- fluxos;
- tabelas;
- blocos de explicação;
- diagramas simples.

---

## 7. Slide de agenda / sumário

Estrutura vertical.

Cada item possui:

**Número** à esquerda  
**Título** no centro/esquerda  
**Tema-chave** à direita

Exemplo:

`1` — `O problema: por que RAG?` — `MEMÓRIA & ALUCINAÇÃO`

`2` — `Embeddings e busca vetorial` — `SIGNIFICADO EM COORDENADAS`

`3` — `Reranking` — `QUALIDADE DO CONTEXTO`

### Visual

- Linha horizontal fina separando cada item.
- Número em azul.
- Título em preto e semibold.
- Descrição em cinza e caixa alta.
- Muito espaço vertical entre linhas.

---

## 8. Slides divisores de seção

Fundo:

`#0A0A14`

Número enorme em azul:

`1`

Título enorme em branco:

`O problema: por que RAG?`

Subtítulo pequeno:

`MEMÓRIA, CONTEXTO E ALUCINAÇÃO`

### Característica

O slide divisor deve conter **pouquíssimo conteúdo**.

Sua função é criar ritmo e separar blocos conceituais da aula.

---

## 9. Cards

### Aparência

- Fundo branco.
- Borda `#E6E6EC`.
- Cantos arredondados: ~20–28 px.
- Sem sombra forte.
- Padding amplo.
- Título curto.
- Label pequena acima.
- Texto de 2–4 linhas.

### Card ativo

Para destacar o conceito principal:
- Fundo azul `#350EFF`.
- Texto branco.
- Label branca/azulada.

Exemplo:

```text
MODELO

Modelo de embedding
```

---

## 10. Card destacado com borda

Outra variação observada:

- Fundo branco.
- Borda azul de 1–2 px.
- Cantos bem arredondados.
- Título forte.
- Pode conter uma definição ou mensagem importante.

Use quando quiser dizer:

> "Preste atenção neste conceito."

Não utilizar em todos os cards.

---

## 11. Faixas de destaque

Usar uma faixa horizontal em lavanda muito clara:

`#EEEDF8`

Estrutura:

```text
LABEL    texto principal / insight
```

Exemplo:

`NO PROJETO    Sem RAG, o agente pode inventar especificações...`

A faixa deve ter:
- altura moderada;
- padding horizontal grande;
- texto alinhado verticalmente ao centro;
- sem borda visível.

---

## 12. Fluxos e pipelines

Os fluxos são uma parte importante da linguagem visual.

### Estrutura

Caixas horizontais conectadas por setas:

`Pergunta → Retrieve → Augment → Generate`

### Caixas

- Fundo branco.
- Borda cinza.
- Cantos arredondados.

O passo principal pode ser:
- fundo azul;
- texto branco.

### Setas

- Azul.
- Finas.
- Simples.
- Sem efeitos 3D.

### Regra

Fluxos devem ser lidos da esquerda para a direita sempre que possível.

---

## 13. Diagramas de arquitetura

Utilizar:
- caixas com bordas finas;
- conexões simples;
- poucos componentes;
- hierarquia visual clara.

Exemplo:

```text
Agent
  |
  +---- Tool
  |
  +---- Memory
  |
  +---- Other Agent
```

O componente principal pode ser preenchido em azul.

Componentes secundários permanecem brancos.

---

## 14. Tabelas

As tabelas seguem uma linguagem editorial, não uma tabela tradicional pesada.

### Estrutura

- Cabeçalho simples.
- Linhas separadas por linhas horizontais finas.
- Pouco ou nenhum preenchimento.
- Destaques pontuais em azul.

Evitar:
- linhas verticais em excesso;
- fundos coloridos em todas as células;
- bordas pesadas.

---

## 15. Comparações

Para comparar dois conceitos:

### Layout recomendado

Duas colunas de largura semelhante.

Cada coluna:
- label;
- título;
- 3–4 pontos explicativos.

Uma das colunas pode receber:
- borda azul;
- ou leve destaque azul.

Exemplo:

```text
BI-ENCODER                 CROSS-ENCODER
Rápido, aproximado         Preciso, caro
...
```

---

## 16. Slides com grandes frases

Alguns slides devem quebrar totalmente a estrutura de conteúdo.

Fundo azul.

Frase enorme em branco.

Uma expressão-chave pode aparecer em **amarelo claro/dourado** para criar contraste.

Exemplo:

`busque a informação certa`

### Regra

- Uma única mensagem.
- Tipografia gigantesca.
- Quase nenhum elemento adicional.
- Pode incluir um pequeno pipeline na parte inferior.

---

## 17. Uso de destaque tipográfico

Usar **bold dentro de parágrafos** para palavras essenciais.

Exemplo:

`excelente em linguagem, frágil em fatos específicos`

Destaques não devem usar muitas cores diferentes.

Preferência:
- preto + bold;
- azul para labels;
- branco + azul em slides escuros.

---

## 18. Ícones e ilustrações

A linguagem visual não depende de ilustrações complexas.

Priorizar:
- formas geométricas;
- linhas;
- setas;
- círculos;
- cards;
- números grandes.

Quando ícones forem necessários:
- line icons;
- espessura consistente;
- monocromáticos;
- preferencialmente azul/preto.

Evitar:
- emojis;
- ilustrações 3D;
- ícones multicoloridos;
- stock photos;
- elementos decorativos aleatórios.

---

## 19. Formas geométricas

Elemento recorrente:

**linhas angulares abstratas grandes**.

Características:
- outline;
- stroke fino;
- cor lavanda/azul claro;
- baixa opacidade;
- parcialmente fora do canvas;
- composição assimétrica.

Usar principalmente:
- capa;
- separadores;
- slides especiais.

Não usar em todo slide.

---

## 20. Ritmo da apresentação

A sequência visual ideal é:

```text
CAPA
  ↓
AGENDA
  ↓
DIVISOR
  ↓
CONTEÚDO
  ↓
CONTEÚDO
  ↓
FLUXO / DIAGRAMA
  ↓
SLIDE DE IMPACTO
  ↓
DIVISOR
  ↓
CONTEÚDO
```

Misturar slides densos com slides extremamente simples evita fadiga visual.

---

## 21. Regras de composição

### Fazer

- Alinhar tudo em um grid.
- Usar títulos grandes.
- Deixar espaço vazio.
- Trabalhar com 1 ideia principal.
- Destacar apenas o que é importante.
- Manter consistência de margens.
- Usar azul como acento, não como decoração constante.

### Evitar

- Texto centralizado em slides de conteúdo.
- Parágrafos longos.
- Mais de 3–4 cards grandes por slide.
- Muitos tamanhos de fonte.
- Muitas cores.
- Sombras fortes.
- Gradientes desnecessários.
- Clutter visual.

---

## 22. Template de slide de conteúdo

```text
┌────────────────────────────────────────────────────────────┐
│ EYEBROW                                                    │
│                                                            │
│ Título principal                                           │
│                                                            │
│ Conteúdo                                                   │
│                                                            │
│ ┌─────────────┐   ┌─────────────┐   ┌─────────────┐       │
│ │ LABEL       │   │ LABEL       │   │ LABEL       │       │
│ │ Título      │   │ Título      │   │ Título      │       │
│ │ Texto       │   │ Texto       │   │ Texto       │       │
│ └─────────────┘   └─────────────┘   └─────────────┘       │
│                                                            │
└────────────────────────────────────────────────────────────┘
```

---

## 23. Template de divisor

```text
┌────────────────────────────────────────────────────────────┐
│                                                            │
│  2                                                         │
│                                                            │
│  Embeddings e busca vetorial                              │
│                                                            │
│  COMO A MÁQUINA "ENTENDE" TEXTO                            │
│                                                            │
└────────────────────────────────────────────────────────────┘
```

Fundo preto.

Número azul gigante.

Título branco.

---

## 24. Template de slide de impacto

```text
┌────────────────────────────────────────────────────────────┐
│                                                            │
│  Em vez de confiar só na memória do                        │
│  modelo, **busque a informação certa** e                   │
│  entregue junto da pergunta.                               │
│                                                            │
│                                                            │
│  [ Retrieve ] → [ Augment ] → [ Generate ]                 │
│                                                            │
└────────────────────────────────────────────────────────────┘
```

Fundo azul.

Texto branco.

Palavra/frase principal em amarelo claro.

---

## 25. Regra de ouro

> **A apresentação deve parecer mais próxima de um editorial de tecnologia do que de um PowerPoint corporativo tradicional.**

A prioridade visual é:

**hierarquia > espaço > tipografia > estrutura > decoração.**
