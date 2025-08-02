# 🧾 Documentação de Qualidade: User Stories na Prática

[📖 Documentação Completa no Miro](https://miro.com/app/board/uXjVJbf3FUE=/?share_link_id=300042583615)  

Este repositório é parte do meu processo de aprendizado em QA. Aqui documento, de forma prática e estratégica, o uso de **user stories, regras de negócio e critérios de aceite** como base para requisitos e testes de software.

A ideia é treinar a clareza na escrita técnica, criar uma estrutura consistente para funcionalidades e exercitar o olhar crítico sobre o que deve ser testado em uma aplicação.

---

## 🧠 O que são User Stories?

User stories são descrições curtas e simples de funcionalidades, escritas da perspectiva do usuário final. Elas ajudam a alinhar o entendimento entre time de desenvolvimento, QA e stakeholders.

Com uma boa user story, é possível:
- Entender a real necessidade do usuário
- Definir regras de negócio com clareza
- Criar critérios de aceite objetivos
- Guiar testes manuais ou automatizados

---

## ✍️ Estrutura da Documentação

A estrutura deste repositório segue o seguinte padrão para cada funcionalidade:

### 🧩 Funcionalidade

Nome e breve descrição da funcionalidade documentada.

### 📝 User Story

História do usuário no formato:
Eu como [tipo de usuário]
Gostaria de [ação/função]
Porque [benefício/objetivo]


### 📌 Regras de Negócio

Regras específicas que devem ser respeitadas na funcionalidade. Exemplo:
- RN1: O campo de input deve conter o placeholder "O que preciso fazer?"

### ✅ Critérios de Aceite

Critérios que definem quando a funcionalidade pode ser considerada pronta, geralmente no formato Gherkin:
```gherkin
Cenário: Adicionar item na lista
Dado que estou na aplicação
Quando visualizo o campo de input
Então consigo digitar um texto
E o campo exibe o placeholder "O que preciso fazer?"
```

---

### 🛠️ Objetivo do Projeto
Praticar escrita técnica para QA

Simular funcionalidades reais em um formato documentado

Reforçar o uso de critérios de aceite como base para testes

Criar um repositório público com foco em documentação de q



