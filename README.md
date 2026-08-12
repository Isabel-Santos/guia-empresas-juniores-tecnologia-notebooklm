# O Guia das Empresas Juniores de Tecnologia do Brasil — NotebookLM

Este repositório contém o projeto desenvolvido para o Lab **"Acelere sua Aprendizagem com IA: Explore o Poder do NotebookLM no Google"** da [Digital Innovation One (DIO)](https://www.dio.me/).

O objetivo deste projeto é explorar o **NotebookLM** da Google como ferramenta de sintetização e estudo sobre o **Movimento Empresa Júnior (MEJ)** focado na área de **Tecnologia da Informação** no Brasil.

---

## Contexto e Objetivos de Estudo

- **Tema:** Mapeamento e Análise das Empresas Juniores de Tecnologia no ecossistema universitário brasileiro.
- **Objetivos:**
  1. Compreender o impacto do MEJ na formação prática de profissionais de TI.
  2. Mapear o portfólio de serviços (desenvolvimento web, apps, consultoria) oferecido pelas EJs brasileiras.
  3. Criar um material de consulta rápida e reutilizável utilizando Inteligência Artificial baseada em fontes confiáveis.

*"Este estudo foi aplicado na prática como pesquisa fundacional para a criação de uma nova Empresa Júnior de Tecnologia"*

---

## Curadoria de Fontes

Foram selecionadas e carregadas as seguintes fontes abertas no NotebookLM:

1. **CJR (UnB):** Empresa Júnior de Computação da Universidade de Brasília.
2. **InfoJr (UFBA):** Empresa Júnior de Informática da Universidade Federal da Bahia.
3. **ECOMP (UFPR):** Associação Júnior de Consultoria em Informática da UFPR.
4. **EJCM (UFRJ):** Desenvolvimento de Sites, Sistemas e Aplicativos.
5. **IDE (UFRGS/UFSM/Afya):** Estudos de caso e vantagens de participação em EJs de tecnologia.

---

## Engenharia de Prompts & "Cicatrizes" (Troubleshooting)

Durante a interação com o NotebookLM, foram testadas diferentes abordagens de prompts para garantir respostas concisas e fundamentadas estritamente nas fontes:

### Prompt 1: Panorama Geral
- **Pergunta:** *"Qual o papel das Empresas Juniores de Tecnologia na formação dos alunos no Brasil?"*
- **Resultado:** A IA gerou um resumo consistente destacando o aprendizado prático, governança e responsabilidade social.

### Prompt 2: Criação de Glossário
- **Pergunta:** *"Liste os 10 principais termos e conceitos do MEJ em TI presentes nas fontes."*
- **Resultado:** Glossário gerado englobando termos como MEJ, Consultoria em TI, Projetos Fullstack, Mentoria Docente e Portfólio de Soluções.

### Cicatrização (Troubleshooting / Refinamento)
- **Desafio:** No prompt de comparação de serviços, a resposta inicial veio genérica e não identificava quais EJs faziam o quê.
- **Ajuste realizado:** Refinei o prompt exigindo: *"Cite nominalmente as EJs presentes nas fontes e estruture os serviços em formato de tabela Markdown"*. O resultado foi preciso e 100% fiel aos documentos.

---

## Guia de Estudos & Tabela de Resultados

### Tabela de EJs e Portfólio de Serviços
| Empresa Júnior | Instituição | Foco de Atuação |
| :--- | :--- | :--- |
| **CJR** | UnB | Desenvolvimento de Software, Web e Mobile |
| **InfoJr** | UFBA | Soluções Web, Sistemas e Consultoria em TI |
| **ECOMP** | UFPR | Consultoria em Informática e Desenvolvimento |
| **EJCM** | UFRJ | Aplicações Web e Sistemas sob Medida |

### Glossário Rápido
- **MEJ:** Movimento Empresa Júnior, focado na vivência empresarial antes do mercado de trabalho.
- **Desenvolvimento sob Medida:** Criação de software personalizado atendendo às necessidades específicas de micro e pequenas empresas.

---

## Recursos Multimídia do NotebookLM
- **Resumo em Áudio (Audio Overview):** Podcast sintético gerado via NotebookLM abordando o ecossistema das EJs de tecnologia no Brasil.

---

## Prompts Reutilizáveis para Revisão
```text
- "Quais as principais habilidades técnicas que um membro de EJ de TI desenvolve segundo as fontes?"
- "Crie 5 perguntas de múltipla escolha com gabarito sobre o funcionamento de uma Empresa Júnior de TI."
