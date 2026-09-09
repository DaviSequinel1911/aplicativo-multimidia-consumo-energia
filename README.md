# Aplicativo Multimídia Educacional — Consumo de Energia Elétrica

Aplicativo interativo desenvolvido em **Processing**, com o objetivo de ensinar conceitos de **potência e consumo de energia elétrica** para alunos do ensino fundamental, através de explicações teóricas, exemplos de cálculo e exercícios de fixação.

Este repositório é uma **cópia (fork) do projeto original**, feita por mim para documentar e apresentar minha contribuição real no desenvolvimento. Todos os créditos pela concepção e desenvolvimento do projeto são do grupo abaixo.

> 🔗 **Repositório original (equipe):** https://github.com/yann-maia/APLICATIVO-MULTIMIDIA

---

## Parte 1 — Sobre o Projeto

**O que é:** um aplicativo educacional multimídia que guia o usuário por telas de teoria, fórmulas e exemplos práticos sobre potência elétrica (Watts, kWh, bandeiras tarifárias, eficiência de lâmpadas LED vs. incandescentes), finalizando com um questionário de perguntas e respostas para testar o conhecimento.

**Contexto:** projeto desenvolvido em equipe durante o primeiro período do curso de Ciência da Computação (PUCPR), para uma disciplina que exigia o uso de Inteligência Artificial como ferramenta de apoio ao aprendizado — muitos dos conceitos técnicos envolvidos (Processing, estruturação de telas, lógica do app) ainda eram novos para a equipe.

**Tecnologias:**
- **Processing** (linguagem baseada em Java) para toda a interface e lógica do aplicativo
- Estrutura de telas modular: menu, teoria, cálculos, perguntas, revisão, resumo e créditos
- Assets próprios (imagens de fórmulas, selo Procel, bandeiras tarifárias, comparativo LED x incandescente)

**Estrutura do código:**
| Arquivo | Função |
|---|---|
| `Main.pde` | Ponto de entrada e controle geral das telas |
| `MenuScreen.pde` | Tela inicial / menu de navegação |
| `TheoryScreen.pde` | Conteúdo teórico sobre potência elétrica |
| `QuestionsScreen.pde` | Perguntas do questionário |
| `AnswersScreen.pde` | Gabarito / respostas |
| `ReviewScreen.pde` | Tela de revisão do conteúdo |
| `SummaryScreen.pde` | Resumo final |
| `CreditsScreen.pde` | Créditos da equipe |
| `ClassScreen.pde`, `ClassButton.pde`, `ClassTheme.pde` | Classes de apoio (botões, temas visuais, estrutura de telas) |
| `Data.pde` | Dados e conteúdo usados pelo app |
| `Utils.pde` | Funções utilitárias |

**Sobre esta versão:** o código aqui presente é a **versão final corrigida** do projeto — a mesma que foi de fato empacotada no instalador/executável entregue para a disciplina, incluindo pequenos ajustes feitos após uma versão intermediária (como a correção da cor de estados de erro e um ajuste no texto de instruções do questionário).

---

## Parte 2 — Minha Contribuição

Minha responsabilidade no projeto foi **elaborar o conteúdo educacional e implementá-lo no aplicativo**, com foco em atender as dificuldades reais de aprendizado identificadas na turma-alvo (alunos do ensino fundamental). Isso incluiu:

- **Levantamento de conteúdo:** definir quais conceitos de potência e consumo elétrico precisavam ser explicados de forma mais simples e visual, com base nas dúvidas comuns identificadas.
- **Redação do material teórico e dos exercícios:** escrever as explicações, exemplos de cálculo e as perguntas do questionário de forma didática, adequada ao público do fundamental.
- **Implementação no app:** integrar esse conteúdo às telas (`TheoryScreen`, `QuestionsScreen`, `AnswersScreen`, `Data`), garantindo que a informação aparecesse de forma clara na interface construída pela equipe.
- **Uso de IA como apoio de aprendizado:** como parte dos requisitos da disciplina, usei IA (Claude) para entender conceitos técnicos de Processing e da estrutura do app que ainda eram novos para mim e para o restante da equipe, aplicando o que aprendi diretamente na implementação do conteúdo.

O restante da estrutura do aplicativo (arquitetura de telas, classes de apoio, lógica de navegação) foi desenvolvido em conjunto com os demais integrantes da equipe, listados no repositório original.

---

## Como executar

1. Instale o [Processing](https://processing.org/download).
2. Abra a pasta deste repositório no Processing (arquivo principal: `Main.pde`).
3. Clique em **Run** ▶.

---

## Créditos

Projeto original desenvolvido em equipe — veja a lista completa de integrantes e a versão original em: https://github.com/yann-maia/APLICATIVO-MULTIMIDIA
