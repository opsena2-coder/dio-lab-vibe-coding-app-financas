# 💸 App S&B Finanças Pessoais com Vibe Coding



- Seu **prompt final** (PRD);
App de Finanças Pessoais Minimalista (MVP) moderno e escalável.

ETAPA 1 - Estrutura Base e Autenticação:

Visão do Produto:
Aplicativo de finanças pessoais simples, intuitivo e minimalista para controle de receitas e despesas, com estrutura preparada para multiusuário no futuro.

Implemente:
1. Autenticação com Supabase (login, cadastro e logout).
2. Estrutura de usuários vinculando dados financeiros por user_id.
3. Layout principal com sidebar (desktop) e bottom navigation (mobile).
4. Dashboard inicial com resumo financeiro do mês atual.

Especificações:
- Stack: React + Tailwind + Supabase.
- Tabela users (auth padrão Supabase).
- Tabela transactions:
  id (uuid)
  user_id (uuid, foreign key)
  type ("income" | "expense")
  category (string)
  description (string)
  amount (decimal)
  date (date)
  created_at (timestamp)
- Sempre filtrar dados por user_id autenticado.
- Valores monetários formatados em R$.

UI/Design:
- Estética minimalista estilo fintech moderna.
- Cores principais: verde suave para receitas, vermelho suave para despesas, base neutra (cinza claro/branco).
- Tipografia limpa e moderna.
- Cards com sombra sutil e bordas arredondadas.
- Totalmente responsivo (mobile-first).
- UI bonita, harmônica, intuitiva, moderna, baseada nas melhores práticas recomendadas com premiações de design e UX dos últimos anos.

NÃO implemente ainda:
- Metas financeiras
- Cartões de crédito
- Integrações bancárias
- Investimentos

----------------------------------------

ETAPA 2 - CRUD de Transações:

Implemente:
1. Tela de listagem com filtro por mês.
2. Botão “Nova Transação” com modal ou página dedicada.
3. Campos obrigatórios: tipo, valor, categoria, data.
4. Edição e exclusão com confirmação.

Comportamentos:
- Validação de valor > 0.
- Atualização automática do dashboard após inserção.
- Ordenação por data (mais recente primeiro).

NÃO implemente:
- Categorias avançadas com hierarquia.
- Importação de arquivos.

----------------------------------------

ETAPA 3 - Dashboard Resumido:

Implemente:
1. Cards de resumo: Total Receitas, Total Despesas, Saldo.
2. Gráfico simples (barra ou pizza) mostrando proporção receitas vs despesas.
3. Cálculo automático baseado no mês selecionado.
4. Indicador visual positivo (saldo verde) ou negativo (saldo vermelho).

NÃO implemente:
- Relatórios avançados
- Comparações entre meses
- Exportação de dados
  
- Prints ou pequenos vídeos das interações com a IA;

- <img width="886" height="413" alt="image" src="https://github.com/user-attachments/assets/52e5c233-60f8-4b7e-a6bc-a0412cedbcfa" />
  <img width="886" height="434" alt="image" src="https://github.com/user-attachments/assets/040e595b-fa36-4dfa-8812-ca10241d8e3d" />

- Um resumo do que o seu **App de Finanças Pessoais** faz;

- Faz u controlhe dos lançaentos de gastos diverços e inclusão da descrição dos lançamentos.
    
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
  - Todas as opções implementadas no App estão funcionando corretamente. O mesmo possui também tela de Login que é validada por cadastro e confirmação de e-mmail.
  
  - O que não funcionou como o esperado?
  - Até o momento não está apresentando nenhuma estabilidade.
  -  
  - O que aprendeu sobre conversar com IAs?
  - Hojé aprendi que ela é uma ferrementa iprescidível para nos ajudar a tirar dúvidas e criar ferraentas para a nossa atualidade.

> [!TIP]
> [Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.](https://id-preview-969b0187--eb5a12bb-7c38-4e1b-9ee8-42e503df9c08.lovable.app/)

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
