# 💸 App de Finanças Pessoais do Venilton com Vibe Coding

Este projeto foi desenvolvido como um Desafio de Projeto da DIO de Vibe Coding utilizando o Replit e o ChatGPT. A proposta é criar um aplicativo de organização financeira pessoal baseado em interações em linguagem natural.

---

## 📝 PRD Refinado no ChatGPT

```markdown
# PRD – Aplicativo de Organização de Finanças Conversacional

## 1. Contexto

O objetivo é criar um aplicativo web responsivo de Organização de Finanças Pessoais que permita registrar e acompanhar gastos de forma simples, acessível e conversacional.

O diferencial do produto é oferecer duas formas de interação:

* 🗨️ Modo Conversacional (via chat em linguagem natural)
* 📋 Modo Estruturado (entrada rápida e direta)

A proposta é reduzir fricção cognitiva e tornar o controle financeiro mais intuitivo para iniciantes.

---

## 2. Problema

Muitas pessoas abandonam aplicativos financeiros porque:

* Exigem entrada manual complexa
* Possuem interfaces sobrecarregadas
* Demandam múltiplas decisões por registro
* Oferecem análises pouco práticas

O App resolve isso por meio de:

* Interação simplificada
* Confirmações rápidas
* Design escuro de alto contraste
* Recomendações financeiras realistas e acionáveis

---

## 3. Público-Alvo

Pessoas iniciantes em organização financeira que:

* Desejam praticidade
* Não gostam de planilhas
* Precisam de clareza visual
* Querem orientação simples e prática

---

## 4. Proposta de Valor

Um aplicativo financeiro que:

* Permite escolher como interagir (conversa ou estrutura)
* Reduz decisões desnecessárias
* Oferece feedback visual direto com gráficos simples
* Sugere melhorias práticas com base nos maiores gastos

Sem julgamentos. Sem complexidade desnecessária.

---

## 5. Funcionalidades-Chave do App

### 5.1. Escolha de Modo de Interação

A cada novo registo, a pessoa usuária pode optar por escolher entre:

**Modo Conversacional**

* Registro de gastos via linguagem natural
  Exemplo:

  > “Gastei 45 reais no mercado”

**Modo Estruturado**

* Campos simples:

  * Valor
  * Categoria (selecionável)
  * Data (automática por padrão)
  * Botão “Salvar”

A pessoa usuária pode alternar entre modos a qualquer momento.

---

### 5.2. Classificação Automática com Confirmação Rápida

Após registrar um gasto no modo conversacional:

O sistema:

1. Identifica valor
2. Sugere categoria automaticamente
3. Exibe confirmação simples:

> R$ 45 – Categoria: Alimentação
> Confirmar? [Sim] [Alterar]

Objetivo: evitar múltiplas decisões e reduzir fricção.

---

### 5.3. Design Escuro de Alto Contraste

* Tema padrão escuro
* Alto contraste entre texto e fundo
* Interface limpa
* Tipografia legível
* Sem excesso de elementos visuais
* Botão para página de relatório.

Foco em clareza e redução de sobrecarga visual.

---

### 5.4. Metas Financeiras com Barra de Progresso

A pessoa usuária pode:

* Criar meta (ex: Guardar R$ 1000)
* Definir prazo opcional
* Acompanhar progresso com:

  * Barra visual simples
  * Percentual claro
  * Valor acumulado exibido

Exemplo:

> Meta: R$ 1000
> Progresso: 40% (R$ 400 guardados)

Apenas progresso direto. A meta pode ser criada clicando em um botão e preenchendo um formulário básico ou por chat, onde a pessoa usuária fala qual meta quer criar e ela é registrada dentro do campo de categorias.

---

### 5.5. Dicas Financeiras Baseadas nos Maiores Gastos

O sistema analisa:

* Categoria com maior volume de gasto no período
* Frequência de transações

Com base nisso, o “Agente Financeiro” oferece:

* Dicas práticas
* Sugestões realistas
* Linguagem não julgadora

Exemplo:

> “Percebi que Alimentação foi sua maior categoria este mês.
> Quer testar cozinhar 2 dias a mais por semana para reduzir pedidos?”

As dicas devem:

* Ser acionáveis
* Ser simples
* Não culpar a pessoa usuária

---

### 5.6. Relatórios Simples

Exibição de:

* Total gasto no mês
* Total por categoria
* Maior gasto do período
* Histórico cronológico

Priorizar:

* Texto explicativo claro
* Visual minimalista

---

## 6. Estrutura de Telas do App

1. Tela Inicial

   * Tela de login ou cadastro, com campos de usuário e senha

2. Tela de Escolha

   * Dois botões para escolher se quer ir para área de chat ou formulário

2.1. Tela de chat

   * Resumo rápido do mês na parte superior (entradas, saídas e saldo)
   * Área de chat, onde as informações serão registradas e exibidas (metas, relatórios, entradas, saídas, dicas, etc)
   * Botão para a lista de metas
   * Botão para a página do relatório

2.2. Tela de Formulário

   * Resumo rápido do mês na parte superior (entradas, saídas e saldo)
   * Lista de metas com o botão de formulário para adicionar meta
   * Botão para a página relatório
   * Botão para dicas financeiras (abre um chat para pedir dicas)


3. Tela de Metas

   * Lista de metas
   * Barra de progresso

4. Tela de Relatórios

   * Resumo do mês
   * Gastos por categoria
   * Histórico

A **página de relatório** também mostra informações em forma de gráfico. Ela pode aplicar filtros para visualização dos gastos por mês ou por categorias.

O **gráfico por mês** é um gráfico donut precisa ter uma opção em lista para selecionar qual mês e qual o ano de referência. Ele mostra a porcentagem de gastos por categoria dentro do mês selecionado.

O **gráfico por categoria** é um gráfico em barras, que mostra o valor gasto dentro da categoria em cada mês.

---

## 7. Recursos Técnicos Necessários (Replit)

* Frontend responsivo (HTML + CSS + JS ou React)
* Tema escuro com alto contraste
* Lógica de:

  * Extração de valor do texto
  * Sugestão de categoria por palavras-chave
  * Cálculo de metas
  * Análise de maior categoria
* Armazenamento simples:

  * JSON local
    ou
  * Banco leve (ex: SQLite)
```

---

## 💬 Interações com o Replit

> Enviei o PRD e esperei gerar o aplicativo (9 min)

> "Faça uma tela mais simples de Login, apenas com o nome do app "FinAI" e um campo para e-mail e senha ou um botão de cadastro. Sem mais informações."

> O Assistente IA não está se comunicando com a página de metas. Não é possível criar uma meta pelo chat e nem mesmo adicionar valores a metas existentes através dele. Faça a conexão entre o Assistente IA e as metas. Também adicione uma janela pop-up dentro do site, com o design da plataforma, para adicionar os valores guardados para meta (atualmente é por um pop-up do navegador, e eu quero um do app).

---

## 🎯 Resultado Final

Acesse o protótipo funcional no Replit:  
**[FinAI](https://finance-organizer--goncalvesanurb.replit.app)**

<img width="1910" height="915" alt="image" src="https://github.com/user-attachments/assets/9eea9dfa-466b-4152-8a34-229f73e91bc1" />

<img width="1910" height="915" alt="image" src="https://github.com/user-attachments/assets/ca2cd533-fc9b-46db-93ed-f2a181aaa58e" />

<img width="1910" height="915" alt="image" src="https://github.com/user-attachments/assets/1db39afc-668e-4ae1-a039-8542fd09965b" />


---

## 🔍 Funcionalidades do App de Organização Financeira – FinAI

### 1. Autenticação e Acesso Seguro

* Tela de login/cadastro integrada
* Campos de:

  * E-mail
  * Senha
* Botão único para entrar ou criar conta
* Interface escura, limpa e de alto contraste
* Sessão personalizada com identificação do usuário no menu lateral

Objetivo: acesso rápido, direto e sem ruído visual.

---

### 2. Dashboard Financeiro (Visão Geral)

Tela principal com panorama mensal claro e objetivo:

* **Saldo Atual**
* **Receitas**
* **Despesas**

Diferenciação visual consistente:

* Verde para entradas
* Vermelho para saídas

Inclui também:

#### Últimas Transações

* Lista cronológica
* Exibe:

  * Categoria
  * Data
  * Descrição
  * Valor com indicação visual de entrada ou saída

Permite compreensão imediata da situação financeira sem precisar navegar por gráficos complexos.

---

### 3. Assistente IA (Modo Conversacional)

Interface de chat integrada ao sistema:

* Mensagem inicial orientando o uso em linguagem natural
* Campo fixo inferior para digitação
* Registro de gastos e ganhos via texto livre

Exemplo de uso:

* “Gastei 50 no iFood”
* “Recebi 2000 de salário”

Funções principais:

* Interpretação de valor e tipo de transação
* Classificação automática
* Registro direto no sistema

Objetivo: reduzir fricção e evitar formulários longos.

---

### 4. Lançamento Manual (Modo Estruturado)

Tela dedicada para quem prefere controle direto:

* Alternância entre:

  * **Despesa**
  * **Receita**

Campos disponíveis:

* Valor (R$)
* Categoria (seleção)
* Data
* Descrição opcional

Botão destacado:

* “Salvar Lançamento”

Ideal para:

* Pessoa usuárias que preferem previsibilidade
* Registros mais detalhados
* Ajustes ou correções

---

### 5. Metas Financeiras

Área específica para criação e acompanhamento de objetivos financeiros.

Cada meta apresenta:

* Nome da meta
* Valor atual acumulado
* Valor total desejado
* Percentual de progresso
* Barra visual de progresso

Ações disponíveis:

* Botão “Nova Meta”
* Botão “Guardar Valor” em cada meta

Interface simples:

* Sem gráficos complexos
* Apenas progresso claro e percentual visível

---

### 6. Relatórios Financeiros

Tela analítica com duas visualizações principais:

#### Despesas por Categoria

* Gráfico de rosca (donut)
* Destaque visual da categoria predominante
* Legenda clara

#### Receitas vs Despesas (Mensal)

* Gráfico comparativo de entradas e saídas
* Escala vertical objetiva
* Período mensal destacado

Objetivo:

* Visualização rápida de padrões
* Análise sem excesso de informação

---

### 7. Navegação Estruturada

Menu lateral fixo com acesso a:

* Dashboard
* Assistente IA
* Lançamento
* Metas
* Relatórios

Inclui:

* Identificação do usuário
* Botão de sair destacado

A navegação é:

* Previsível
* Consistente
* Sem menus escondidos

---

### 8. Sistema de Organização Visual

O app adota um padrão visual consistente:

* Tema escuro predominante
* Alto contraste
* Hierarquia tipográfica clara
* Cores com função semântica:

  * Verde = positivo
  * Vermelho = negativo
* Espaçamento adequado entre elementos

Resultado:

* Leitura rápida
* Menor sobrecarga visual
* Experiência estável e organizada

---

### 9. Estrutura de Interação Dual

O aplicativo permite dois modelos de uso:

* **Conversacional (Assistente IA)**
* **Estruturado (Lançamento Manual)**

---

## 🧠 Reflexão

### O que funcionou bem?  
Usar uma IA Generativa para refinar o PRD foi bem interessante, porque os sites que geram aplicações costumam ter um limite de gratuidade.
Também pedi dicas para o ChatGPT de funcionalidades que eu poderia adicionar conforme interesses pessoais meus.

### O que não funcionou como o esperado?  
O Repplit tem uma limitaçãode interações diárias por dia. Isso significa que o tempo para o aplicativo ficar perfeitamente como desejado usando só vibe codding levaria algum tempo.

### O que aprendi sobre conversar com IAs?  
Quanto mais específico e detalhado o prompt, mais chances de conseguir um bom resultado com menos entradas.
Nunca fica perfeito de primeira, então é preciso entender o que não ficou perfeitamente como esperado para conseguir refinar com precisão.
