# 🧾 Sistema de Controle de Leilões

Sistema web desenvolvido para facilitar o registro e o controle de arremates em leilões presenciais.

A aplicação permite registrar rapidamente os produtos arrematados, identificar os participantes, acompanhar pagamentos e calcular automaticamente os valores individuais e gerais do evento.

O sistema foi pensado para ser simples e rápido durante o leilão, funcionando em **celulares, tablets, notebooks e computadores**.

---

## 🎯 Objetivo

Durante um leilão, vários arremates acontecem em sequência e as informações precisam ser registradas rapidamente.

O objetivo deste projeto é substituir anotações manuais e cálculos feitos no papel por uma ferramenta digital simples e organizada.

Com o sistema é possível registrar:

- Produto arrematado
- Nome do arrematante
- Valor do arremate
- Status do pagamento
- Forma de pagamento

No momento do pagamento, o responsável consegue localizar rapidamente todos os arremates de uma pessoa e visualizar o valor total a pagar.

---

## ✨ Principais funcionalidades

### 📝 Registro rápido de arremates

Permite cadastrar:

- Produto
- Arrematante
- Valor
- Status do pagamento

Novos arremates são registrados inicialmente como **Pendentes**.

---

### 💰 Controle de pagamentos

O pagamento é realizado posteriormente, normalmente no encerramento do leilão.

O sistema permite registrar:

- PIX
- Dinheiro
- Outra forma de pagamento

Também apresenta automaticamente:

- Total pago
- Total pendente
- Total geral

---

### 🔎 Pesquisa por arrematante

A pesquisa pelo nome permite localizar rapidamente todos os produtos adquiridos por uma pessoa.

São apresentados:

- Produto
- Valor individual
- Status
- Forma de pagamento
- Total geral
- Total pago
- Total pendente

Essa funcionalidade facilita principalmente o atendimento no momento do fechamento do leilão.

---

### ✏️ Edição de arremates

Um arremate pode ser editado posteriormente.

É possível corrigir:

- Nome do arrematante
- Produto
- Valor
- Status
- Forma de pagamento

A edição altera o registro existente, sem criar um novo arremate.

Os totais são recalculados automaticamente.

---

### 🗑️ Exclusão de registros

O sistema permite:

- Excluir um arremate individualmente
- Excluir todos os arremates do evento

As exclusões possuem confirmação para reduzir o risco de perda acidental de informações.

---

### 🔤 Organização automática

Os arremates são organizados alfabeticamente pelo nome do arrematante.

Quando existem vários arremates para a mesma pessoa, os produtos podem ser organizados de forma complementar.

Essa organização facilita a localização dos participantes durante o fechamento do evento.

---

### 📊 Resumo financeiro

O sistema calcula automaticamente:

| Indicador | Descrição |
|---|---|
| 💰 Total Geral | Soma de todos os arremates |
| ✅ Total Pago | Soma dos arremates pagos |
| ⏳ Total Pendente | Soma dos valores ainda não pagos |

Os valores são atualizados após:

- Novo arremate
- Edição
- Pagamento
- Exclusão

---

## 📄 Exportação de dados

O sistema permite exportar as informações do leilão para utilização fora da aplicação.

### PDF

O relatório pode apresentar:

- Nome do evento
- Data
- Arrematante
- Produto
- Valor
- Status
- Forma de pagamento
- Totais

### Excel

Os dados podem ser exportados para uma planilha permitindo continuidade do trabalho no:

- Microsoft Excel
- LibreOffice Calc
- Google Planilhas

Os valores são exportados como números, possibilitando novos cálculos e utilização de fórmulas.

---

## 📱 Responsividade

A aplicação foi desenvolvida para diferentes tamanhos de tela:

- 📱 Smartphone
- 📲 Tablet
- 💻 Notebook
- 🖥️ Desktop

A interface prioriza botões acessíveis e formulários rápidos para utilização durante o evento.

---

## 🧠 Fluxo de utilização

### Durante o leilão

1. Identificar o produto.
2. Informar o nome do arrematante.
3. Informar o valor.
4. Registrar o arremate.
5. Continuar o leilão.

Os pagamentos permanecem como **Pendentes**.

### No encerramento

1. O participante vai até a mesa de pagamento.
2. O responsável pesquisa o nome.
3. O sistema apresenta todos os produtos adquiridos.
4. O sistema calcula o total.
5. O pagamento é registrado.
6. O status é alterado para **Pago**.

---

## 🛠️ Tecnologias

O projeto utiliza tecnologias modernas para desenvolvimento de aplicações web.

### Front-end

- React
- TypeScript
- Vite
- Tailwind CSS
- HTML5
- CSS3

### Dados e infraestrutura

A arquitetura do projeto está sendo preparada para utilização de:

- Firebase Authentication
- Firebase Firestore

> A utilização efetiva desses serviços depende da configuração e da versão atual do projeto.

---

## 🔐 Segurança e arquitetura

O projeto está sendo estruturado para permitir futuramente:

- Autenticação de usuários
- Separação de dados por cliente
- Separação de dados por evento
- Controle de acesso
- Armazenamento em banco de dados
- Histórico de eventos

A arquitetura poderá permitir a utilização do sistema como uma aplicação online para diferentes organizações e eventos.

---

## 🚀 Possíveis evoluções

O projeto poderá receber novas funcionalidades, como:

- 👤 Cadastro de usuários
- 📅 Múltiplos eventos
- 📚 Histórico de leilões
- 📊 Dashboard
- 💰 Controle de caixa
- 👥 Cadastro de participantes
- 🔢 Número sequencial dos arremates
- 📝 Campo de observações
- 🧾 Impressão de comprovantes
- 🔐 Controle de acesso por evento
- ☁️ Banco de dados em nuvem
- 📱 Aplicativo instalável (PWA)
- 💳 Sistema de assinatura para clientes

---

## 💡 Motivação

Este projeto nasceu da observação de uma necessidade prática: tornar o controle de leilões presenciais mais simples, rápido e organizado.

Processos realizados manualmente podem envolver anotações em papel, procura de nomes e cálculos durante o fechamento do evento.

A proposta é transformar esse processo em uma solução digital acessível e fácil de utilizar.

---

## 👩‍💻 Desenvolvido por

### Edna Silva

Projeto desenvolvido como parte do portfólio de desenvolvimento de soluções digitais.

### Áreas de interesse

- 📊 Dados
- 🤖 Inteligência Artificial
- ⚙️ Automação
- 💻 Sistemas Web
- 📈 Power BI
- 💡 Soluções para problemas reais

---
## 📌 Status do projeto

🟢 **Funcional e em evolução**

O sistema já foi utilizado em um leilão presencial e continua em evolução,
com possibilidade de receber novas funcionalidades e melhorias.

---

## 📄 Licença

Este projeto é destinado a fins de portfólio e demonstração.

O código, a aplicação e seus recursos não devem ser redistribuídos ou utilizados comercialmente sem autorização da autora.
