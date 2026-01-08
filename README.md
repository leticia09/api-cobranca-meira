# api-cobranca-meira

API responsável pelo **envio de mensagens de cobrança via WhatsApp** e **integração com a API do Conta Azul**, facilitando a comunicação com clientes e a automação do processo de cobrança.


## 📌 Visão Geral

Este projeto tem como objetivo centralizar e automatizar cobranças, permitindo:

* 📲 Envio de mensagens de cobrança pelo **WhatsApp**
* 🔗 Integração com a **API do Conta Azul** para consulta e sincronização de dados financeiros
* ⚙️ Configuração flexível de banco de dados via variáveis de ambiente

A aplicação foi desenvolvida pensando em **escalabilidade**, **manutenibilidade** e **boas práticas de engenharia de software**.


## 🛠️ Tecnologias Utilizadas

* **Java 17**
* **Spring Boot**
* **Maven**
* **WhatsApp API / Gateway de Mensagens**
* **Conta Azul API**
* **Banco de Dados** (configurável via variável de ambiente)


## 🚀 Como Executar o Projeto

### Pré-requisitos

* Java 17 instalado
* Maven instalado

### Clonar o repositório

```bash
git clone https://github.com/seu-usuario/api-cobranca-meira.git
cd api-cobranca-meira
```

## Configuração de Variáveis de Ambiente

O projeto utiliza variáveis de ambiente para configuração do banco de dados e integrações externas.


### 🗄️ Banco de Dados

#### Variáveis de ambiente para conexão com banco de dados
- Descrever as variáveis de ambiente para conexão com API Conta Azul


### 📡 Integração com Conta Azul

A API do Conta Azul é utilizada para:

* Consulta de clientes
* Consulta de cobranças e títulos
* Sincronização de informações financeiras

#### Variáveis de ambiente para conexão com API Conta Azul
- Descrever as variáveis de ambiente para conexão com API Conta Azul


### 💬 Envio de Mensagens via WhatsApp

O sistema realiza o envio automático de mensagens de cobrança via WhatsApp, permitindo:

* Mensagens personalizadas
* Disparo automático ou manual
* Integração com dados financeiros do Conta Azul

#### Variáveis de ambiente para conexão com API WhatsApp
- Descrever as variáveis de ambiente para conexão com API WhatsApp

## 🧪 Testes

Para executar os testes:

```bash
mvn test
```


## 🧾 Padrão de Commits

Este projeto segue o padrão **Conventional Commits**:

```
<tipo>(task-jira): descrição curta
```

### Tipos mais utilizados:

* `feat`: nova funcionalidade
* `fix`: correção de bug
* `refactor`: refatoração de código
* `docs`: alterações de documentação
* `test`: criação ou ajuste de testes
* `chore`: tarefas de manutenção

### Exemplos:

```
feat(ADOINCS-123): envio de mensagem automática via WhatsApp
fix(ADOINCS-456): ajuste na autenticação OAuth
```


## 🔗 Jira

* **Projeto Jira:** *https://lelealvesaz.atlassian.net/jira/software/projects/SCRUM/boards/1*
* **Padrão de referência nos commits:**

```
feat(ADOINCS-123): envio de lembrete de pagamento
```

## 🌱 Fluxo de Desenvolvimento (GitFlow)

-   master: produção
-   develop: desenvolvimento
-   feature/\*: novas funcionalidades

Fluxo obrigatório:

feature → develop → master\
Merge somente com aprovação da **Letícia**.

## 🧑‍💻 Comandos Git

``` bash
git checkout develop
git pull origin develop
git checkout -b feature/ADOINCS-123
git add .
git commit -m "feat(ADOINCS-123): descrição"
git push origin feature/ADOINCS-123-descricao
```

## 📄 Licença

Este projeto é de uso privado. Todos os direitos reservados.


## ✨ Autores

Desenvolvido por **Letícia Medeiros & Saron Medeiros**
