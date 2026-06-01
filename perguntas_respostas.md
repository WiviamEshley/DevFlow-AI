# 📄 Questionário Analítico do Projeto - DevFlow AI

Este documento contém as respostas oficiais para as perguntas teóricas exigidas no PDF do projeto DevFLow AI, analisando o comportamento e a configuração do ecossistema multiagente.

---

### 1. Como o papel e a personalidade do seu agente influenciaram as decisões finais?
Cada agente contribuiu para o resultado final de acordo com sua função especializada. 

O Tech Lead AI atuou como orquestrador, analisando o briefing e direcionando o fluxo de trabalho para os demais agentes.

O Analista de Requisitos identificou os requisitos funcionais e não funcionais do sistema, servindo como base para as etapas seguintes.

O Arquiteto de Software influenciou as decisões técnicas ao propor tecnologias e uma arquitetura para o sistema. O Designer de Interface contribuiu com a definição das telas e do fluxo de uso, buscando tornar o sistema mais intuitivo para atendentes e baristas.

O Desenvolvedor de Lógica de Negócio definiu regras, validações e processos relacionados aos pedidos e pagamentos.

O Engenheiro de Testes contribuiu com cenários de validação e identificação de riscos técnicos, enquanto o Redator Técnico consolidou todas as informações em um único documento. Dessa forma, a personalidade especializada de cada agente permitiu que diferentes perspectivas fossem consideradas durante o planejamento do sistema.

### 2. Houve conflitos entre os agentes? Como o orquestrador poderia resolvê-los?
No modelo de coordenação rígida RoundRobinGroupChat, o fluxo é sequencial e circular, o que naturalmente reduz conflitos diretos entre os agentes, já que cada participante possui seu momento específico de contribuição. Dessa forma, não ocorreram conflitos explícitos durante a execução do projeto.
### 3. Quais seriam os riscos se um agente estivesse mal configurado (prompt mal escrito)? Responda para cada agente:
* **Tech Lead AI:** Poderia distribuir tarefas incorretamente ou permitir que os agentes trabalhassem fora do escopo do projeto.
* **Analista de Requisitos:** Poderia criar requisitos inexistentes ou deixar de identificar funcionalidades importantes solicitadas pelo cliente.
* **Arquiteto de Software:** Poderia propor tecnologias inadequadas ou incompatíveis com as necessidades do sistema.
* **Designer de Interface:** Poderia criar telas sem relação com os requisitos definidos, comprometendo a experiência do usuário.
* **Dev de Lógica de Negócio:** Poderia definir regras inconsistentes ou contraditórias, afetando o funcionamento do sistema.
* **Engenheiro de Testes (QA):** Poderia criar testes irrelevantes ou deixar de validar funcionalidades críticas do projeto.
* **Redator Técnico:** Poderia consolidar informações incorretas ou inventar conteúdo não produzido pelos demais agentes, comprometendo a documentação final.

### 4. Que melhorias você faria ou fez para aprimorar a coordenação multiagente?
Durante os testes, foi identificado que alguns agentes produziam respostas muito extensas ou adicionavam informações além do briefing. Para melhorar a coordenação, foram realizados ajustes nos prompts, tornando as instruções mais objetivas e específicas para cada papel.

Também seria interessante implementar validações automáticas pelo Tech Lead AI para verificar se cada agente está respeitando seu escopo antes de encaminhar a tarefa para o próximo participante. Outra melhoria seria restringir ainda mais o contexto compartilhado entre os agentes, permitindo que cada um receba apenas as informações necessárias para sua função.
