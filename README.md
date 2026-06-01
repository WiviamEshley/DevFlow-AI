# 🚀 DevFlow AI

Sistema Multiagente para Planejamento de Projetos de Software utilizando AutoGen Studio e LM Studio.

!<img width="900" height="500" alt="Image" src="https://github.com/user-attachments/assets/175217ac-f3a7-4666-95f2-a03c55073bb9" />

---

## 📖 Sobre o Projeto

O DevFlow AI é uma solução baseada em Inteligência Artificial que utiliza múltiplos agentes especializados para transformar um briefing de negócio em uma documentação técnica estruturada.

Através de uma arquitetura multiagente coordenada pelo AutoGen Studio e executada localmente pelo LM Studio, o sistema simula o trabalho colaborativo de uma equipe de desenvolvimento de software.

---

## 🎯 Objetivo

Automatizar a etapa de planejamento de software, permitindo que um simples briefing seja convertido em:

- Requisitos Funcionais
- Requisitos Não Funcionais
- Arquitetura de Software
- Interface do Sistema
- Regras de Negócio
- Casos de Teste
- Documento Técnico Consolidado

---

## 🏗️ Arquitetura da Solução

<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/d1cfab88-e2d3-4fc0-aa65-bfa356b30005" />

Fluxo de execução:

Cliente → Tech Lead AI → Analista de Requisitos → Arquiteto de Software → Designer de Interface → Desenvolvedor de Lógica → Engenheiro de Testes → Redator Técnico → Documento Final

---

## *Agentes do Sistema*

### - Tech Lead AI
Responsável por analisar o briefing e coordenar o fluxo de trabalho entre os agentes.

### - Analista de Requisitos
Identifica requisitos funcionais e não funcionais a partir do briefing do cliente.

### - Arquiteto de Software
Propõe a arquitetura e as tecnologias adequadas para o sistema.

### - Designer de Interface
Define telas, fluxo de navegação e experiência do usuário.

### - Desenvolvedor de Lógica de Negócio
Especifica processos, regras de negócio e validações.

### - Engenheiro de Testes
Cria casos de teste e identifica possíveis riscos do projeto.

### - Redator Técnico
Consolida todas as contribuições em um documento técnico final.

---

## 🖥️ AutoGen Studio

O AutoGen Studio foi utilizado para criar, configurar e coordenar os agentes da equipe virtual.

<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/cc458a15-5fa3-49ac-885e-b89239cca832" />

Funcionalidades utilizadas:

- Criação de agentes especializados
- Orquestração Round Robin
- Configuração de prompts
- Gerenciamento do fluxo de trabalho

---

## 🤖 LM Studio

O LM Studio foi utilizado para executar localmente o modelo de linguagem responsável pelo comportamento dos agentes.

<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/e2aba342-026f-4187-b52e-d93b14d89bf5" />

Modelo utilizado:

```text
liquid/lfm2.5-1.2b
```

Benefícios:

- Execução local
- Baixo consumo de recursos
- Integração com AutoGen Studio
- Ambiente offline

---

## 📸 Demonstração

### Configuração dos Agentes

![Agentes](./images/agentes.png)

### Execução da Equipe Multiagente

![Execução](./images/execution.png)

### Documento Gerado

![Documento Final](./images/documento-final.png)

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Finalidade |
|------------|------------|
| AutoGen Studio | Coordenação Multiagente |
| LM Studio | Execução Local da LLM |
| LFM 2.5 1.2B | Modelo de Linguagem |
| GitHub | Controle de Versão |
| Markdown | Documentação |

---

## 📚 Aprendizados

Durante o desenvolvimento do DevFlow AI foram explorados conceitos como:

- Inteligência Artificial Generativa
- Engenharia de Prompts
- Sistemas Multiagentes
- Coordenação de Agentes com AutoGen
- Integração com LLMs Locais
- Documentação Automatizada de Software

---

## 👨‍🎓 Projeto Acadêmico

Projeto desenvolvido para fins educacionais na disciplina relacionada à Inteligência Artificial aplicada ao Desenvolvimento de Software.

Curso: Análise e Desenvolvimento de Sistemas  
Instituição: UNINASSAU

---

## ⭐ Conclusão

O DevFlow AI demonstra como múltiplos agentes especializados podem colaborar para transformar um briefing simples em uma documentação estruturada, simulando o trabalho de uma equipe real de desenvolvimento de software e apoiando o processo de planejamento de projetos.
