# 💸 App de Finanças Pessoais do Elton com Vibe Coding

PRD refinado no Copilot Web:

````
# PRD – Aplicativo de Organização de Finanças Pessoais

## 1. Contexto
O aplicativo será um assistente financeiro conversacional, que permite ao usuário organizar suas finanças por meio de diálogos em linguagem natural.  
Objetivo: tornar o controle financeiro simples, acessível e sem burocracia, eliminando a necessidade de formulários complexos ou planilhas.

## 2. Problema
- Usuários desistem de controlar gastos porque os apps atuais exigem entrada manual extensa.  
- Falta de personalização e de uma experiência fluida.  
- Necessidade de uma solução que combine simplicidade, aconselhamento inteligente e acessibilidade para todos.

## 3. Público-Alvo
- Pessoas iniciantes no controle financeiro.  
- Usuários que buscam praticidade e não querem lidar com planilhas ou interfaces complicadas.  
- Jovens adultos e profissionais que desejam melhorar hábitos de consumo.

## 4. Princípios de Design
- Design Universal: o aplicativo deve ser projetado para oferecer uma experiência positiva ao maior número possível de pessoas, independentemente de idade, nível de alfabetização digital ou limitações físicas.  
  - Interface intuitiva e responsiva  
  - Compatibilidade com leitores de tela e comandos de voz  
  - Contraste visual adequado e linguagem clara  
  - Navegação simples e tolerante a erros  
  - Adaptação a diferentes estilos de uso (toque, voz, leitura)

## 5. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural (ex.: “gastei R$50 no mercado”)  
2. Classificação automática das transações em categorias (alimentação, transporte, lazer etc.)  
3. Definição e acompanhamento de metas financeiras (ex.: economizar R$200 por mês)  
4. Agente Financeiro que oferece dicas personalizadas de economia e hábitos saudáveis  
5. Relatórios simples e personalizados, com visualizações claras (gráficos e resumos)

## 6. Entregável da IA
- Plano de MVP contendo:  
  - Principais telas: chat, metas, relatórios  
  - Recursos necessários: NLP para interpretação de linguagem natural, motor de categorização, módulo de relatórios  
  - Esboço de validação inicial: testes com grupo piloto de usuários iniciantes, incluindo pessoas com diferentes perfis de acessibilidade  
- Linguagem acessível e educativa para guiar o usuário no uso

````
Interações com o Lovable:

> Crie um app de finanças pessoais com base no seguinte PRD: {PRD}

> Crie uma tela com relatorio e despesas com graficos de receitas vs despesas, grafico por categoria e extrato completo de transações- acesse pelo botão "relatorios" no topo do dashboard.

Resultado final: https://grana-na-conversa.lovable.app

https://www.awesomescreenshot.com/image/57702079?key=06ad0a6bf417b0250c23da07867080a0

  
# FinanceIA – Organize suas finanças com IA

**FinanceIA** é um aplicativo de organização financeira que utiliza inteligência artificial para oferecer uma experiência simples, acessível e personalizada.  
Ele funciona por meio de conversas em linguagem natural, permitindo que o usuário registre e acompanhe suas finanças sem complexidade.

## Funcionalidades

- **Registro de transações via chat**  
  O usuário informa receitas e despesas com frases naturais, como:  
  `"gastei R$50 no mercado"` ou `"recebi R$3000 de salário"`.

- **Classificação automática de gastos**  
  O assistente identifica a categoria da transação com base na descrição fornecida.

- **Visualização de saldo e resumo financeiro**  
  Cartões com total de receitas, despesas e saldo do mês facilitam o entendimento da situação financeira.

- **Histórico de transações**  
  Lista de entradas e saídas recentes com data, valor e descrição.

- **Definição de metas e acompanhamento** *(planejado no PRD)*  
  O usuário poderá estabelecer objetivos financeiros e monitorar seu progresso.

- **Assistente Financeiro com dicas personalizadas**  
  Sugestões para economizar e melhorar hábitos de consumo com base no perfil do usuário.

- **Design Universal**  
  Interface acessível a todos, com linguagem clara, navegação intuitiva e compatibilidade com tecnologias assistivas.

- **Integração com Lovable Cloud**  
  Banco de dados, autenticação e IA conversacional habilitados via Lovable para facilitar desenvolvimento e escalabilidade.




## Reflexão

### O que funcinou bem?
>Integração com IA conversacional: o uso de linguagem natural para registrar transações funcionou de forma intuitiva e acessível, como planejado no PRD.

>Visualização clara das finanças: os cartões de receitas, despesas e saldo oferecem um resumo direto e fácil de entender, alinhado com a proposta de relatórios simples.

>Classificação automática de transações: o assistente sugere categorias com base na descrição, o que reduz o esforço manual do usuário.

>Design Universal aplicado: a interface é limpa, com instruções claras e acessíveis, respeitando os princípios de inclusão definidos no PRD.

### O que não funcionou como o esperado?
>Falta de metas financeiras no protótipo atual: embora previstas no PRD, ainda não estão implementadas na interface.

>Dicas personalizadas do Agente Financeiro: o assistente ainda não oferece sugestões de economia com base no perfil do usuário, o que limita a personalização.

>Validação com usuários diversos: ainda não foi testado com pessoas de diferentes perfis de acessibilidade, o que é essencial para validar o Design Universal.
### O que aprendeu sobre conversar com IAs?
> Percebi que quanto mais eu explicava o problema, o tipo de usuário e o que o app deveria fazer, mais a IA conseguia me ajudar de forma clara e objetiva. Isso fez toda a diferença na hora de montar o PRD.

