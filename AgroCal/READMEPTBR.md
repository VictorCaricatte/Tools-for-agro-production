# AgroCal - Calculadora de Viabilidade Econômica para Agronegócios

O AgroCal é uma aplicação web desenvolvida para auxiliar usuários na avaliação da viabilidade econômica de projetos no agronegócio. Ele oferece um conjunto abrangente de ferramentas para inserir detalhes do projeto, custos, receitas e, em seguida, calcula indicadores financeiros chave, realiza análises de sensibilidade e auxilia no esboço de um plano de marketing básico.

## Funcionalidades

* **Informações do Projeto:** Defina parâmetros básicos do projeto, como nome, tipo de negócio (aquicultura, pecuária, agricultura, produção industrial, etc.), duração, investimento inicial, Taxa Mínima de Atratividade (TMA), taxa SELIC e inflação esperada.
* **Gerenciamento de Custos:**
    * **Custos Fixos:** Insira e gerencie Despesas de Capital (CAPEX) e Despesas Operacionais (OPEX) com valores mensais.
    * **Custos Variáveis:** Insira e gerencie custos com base no valor unitário e na quantidade mensal.
* **Gerenciamento de Receitas:** Defina fluxos de receita com preço unitário, quantidade mensal e crescimento anual projetado.
* **Cálculo de Impostos:** Insira alíquotas de impostos relevantes (ex: ICMS, PIS, COFINS, Imposto de Renda, CSLL) para serem considerados nas projeções financeiras.
* **Indicadores Financeiros:**
    * Calcula o Valor Presente Líquido (VPL).
    * Calcula a Taxa Interna de Retorno (TIR).
    * Determina os períodos de Payback Simples e Payback Descontado.
    * Exibe o Lucro Líquido Anual Médio e a Rentabilidade.
    * Gera uma tabela de Fluxo de Caixa anual.
* **Análise de Sensibilidade:**
    * Analise o impacto de mudanças em variáveis chave (Receita, Custos Fixos, Custos Variáveis, Investimento Inicial) no VPL do projeto.
    * Visualize os resultados através de tabelas e gráficos.
* **Plano de Marketing e Neuromarketing:**
    * Seções para delinear um Plano de Marketing básico (descrição do produto, público-alvo, diferencial competitivo, precificação, canais, comunicação).
    * Seções para considerar aspectos de Neuromarketing (apelo emocional, facilidade cognitiva, storytelling, elementos sensoriais, gatilhos comportamentais).
* **Relatórios e Gerenciamento de Dados:**
    * Visualize um resumo dos relatórios financeiros e indicadores chave.
    * Gere um relatório detalhado completo do projeto.
    * **Salvar e Carregar Dados:** Persista os dados do projeto localmente no navegador usando o localStorage.
    * **Limpar Dados:** Opção para resetar todas as entradas.
* **Opções de Exportação:**
    * Exporte relatórios e dados para diversos formatos:
        * PDF (Resumo, Relatório Completo, Fluxo de Caixa)
        * Excel (Resumo, Dados Completos, Fluxo de Caixa)
        * CSV
        * JSON
* **Interface do Usuário:**
    * Interface amigável construída com Bootstrap.
    * Inclui um seletor de tema Claro/Escuro para preferência do usuário.
    * Gráficos interativos para visualização de dados financeiros e análise de sensibilidade (usando Chart.js).
    * Navegação por abas para fácil acesso às diferentes seções.
* **Idioma:** A interface da aplicação está em Português (pt-BR).

## Como Usar

1.  Abra o arquivo `Agro2.html` em um navegador web.
2.  Navegue pelas abas no menu à esquerda para inserir os dados do seu projeto:
    * **Informações Básicas:** Preencha os detalhes gerais do seu projeto.
    * **Custos Fixos:** Adicione todos os custos fixos mensais (CAPEX e OPEX).
    * **Custos Variáveis:** Adicione todos os custos variáveis.
    * **Receitas:** Defina suas fontes de receita e expectativas de crescimento.
    * **Impostos e Taxas (implícito nas seções de Receita/Financeiro):** Certifique-se de que as alíquotas de impostos estão configuradas corretamente em seus respectivos campos de entrada.
3.  Após inserir todos os dados, clique no botão "Calcular Tudo", geralmente encontrado na seção "Informações Básicas" ou em uma seção de resumo, para processar os cálculos.
4.  Explore os resultados:
    * **Indicadores Financeiros:** Revise VPL, TIR, Payback e outras métricas. Analise a tabela de fluxo de caixa.
    * **Análise de Sensibilidade:** Realize testes de sensibilidade em diferentes variáveis.
    * **Plano de Marketing:** Preencha os detalhes para sua estratégia de marketing e neuromarketing.
    * **Relatórios:** Visualize relatórios resumidos e gere relatórios detalhados.
5.  Use o menu "Dados" para Salvar seus dados atuais, Carregar dados salvos anteriormente ou Limpar todas as entradas.
6.  Use o menu "Exportar" para baixar seus dados/relatórios nos formatos PDF, Excel, CSV ou JSON.

## Tecnologias Utilizadas

* HTML
* CSS (com Bootstrap 5.3.0)
* JavaScript
* Bootstrap Icons 1.10.0
* Chart.js (para gráficos)
* jsPDF (para exportação em PDF)
* XLSX (SheetJS) (para exportação em Excel)

---
