# Planilha de Custos e Recursos Aprimorada

## Descrição

Este arquivo HTML (`PainelEstrutura.html`) implementa uma planilha dinâmica para gerenciar custos e recursos.  A planilha é estruturada em categorias (ex: Infraestrutura, Equipamentos) e permite adicionar, remover e editar itens em cada categoria.  Os cálculos de valor total por item e totais por categoria são realizados automaticamente.  A planilha também oferece funcionalidades para exportar os dados para PDF e Excel, além de uma função para limpar todos os dados inseridos.

## Funcionalidades

* **Gerenciamento de Categorias:** A planilha é organizada em múltiplas categorias para melhor organização dos itens de custo e recursos.
* **Adicionar/Remover Itens:** Os usuários podem adicionar novas linhas (itens) em cada categoria e remover itens existentes.
* **Edição Dinâmica:** Os campos de entrada (item, quantidade, valor unitário, depreciação) são editáveis, e os cálculos são atualizados em tempo real.
* **Cálculo Automático:** O valor total de cada item é calculado automaticamente (quantidade \* valor unitário).
* **Totais por Categoria:** A planilha calcula e exibe os totais para cada categoria (valor total e depreciação).
* **Totais Gerais:** A planilha calcula e exibe os totais gerais da planilha.
* **Exportação para PDF:** Os dados da planilha podem ser exportados para um arquivo PDF.
* **Exportação para Excel:** Os dados da planilha podem ser exportados para um arquivo Excel.
* **Filtragem de Dados:** Um campo de busca permite filtrar itens em todas as tabelas.
* **Limpar Dados:** Uma função permite limpar (remover) todos os dados inseridos na planilha.
* **Ordenação de Colunas:** As colunas das tabelas podem ser ordenadas clicando nos cabeçalhos das colunas.

## Tecnologias Utilizadas

* **HTML:** Estrutura da página.
* **CSS (Tailwind CSS):** Estilização da página para uma interface amigável e responsiva.
* **JavaScript:** Lógica da planilha (cálculos, adição/remoção de linhas, exportação, filtragem, ordenação).
* **html2pdf.js:** Biblioteca JavaScript para exportar a planilha para PDF.
* **xlsx (js-xlsx):** Biblioteca JavaScript para exportar a planilha para Excel.
* **Google Fonts (Inter):** Fonte utilizada na página.

## Estrutura do Arquivo

O arquivo HTML contém as seguintes seções principais:

* **Cabeçalho:** Título da planilha.
* **Ações Globais:** Barra de ferramentas com botões para buscar, exportar (PDF/Excel) e limpar dados.
* **Área Principal:** Contém as tabelas de dados, organizadas por categoria. Cada categoria possui:
    * Título da categoria.
    * Tabela com cabeçalho (Item, Quantidade, Valor Unitário, Valor Total, Depreciação, Ações).
    * Corpo da tabela (linhas de dados).
    * Rodapé da tabela (totais da categoria).
    * Botão "Adicionar Item".
* **Resumo Geral:** Exibe os totais gerais da planilha.
* **Instruções de Uso:** Fornece orientações sobre como utilizar a planilha.
* **JavaScript:** Contém o código JavaScript para a funcionalidade da planilha.

## Como Usar

1.  Abra o arquivo `PainelEstrutura.html` em um navegador web.
2.  Utilize os botões "Adicionar Item" para incluir novas linhas nas tabelas.
3.  Preencha os campos de entrada nas linhas da tabela.
4.  Os valores totais são calculados automaticamente.
5.  Use os botões de exportação para gerar arquivos PDF ou Excel.
6.  Use o campo de busca para filtrar os itens.
7.  Use o botão "Limpar Dados" para apagar todos os dados (com cuidado).
8.  Clique nos cabeçalhos das colunas para ordenar os dados.

## Notas

* O arquivo utiliza Tailwind CSS para estilização, o que facilita a criação de uma interface moderna e responsiva.
* As bibliotecas `html2pdf.js` e `xlsx` são utilizadas para as funcionalidades de exportação.
* O código JavaScript é responsável por toda a interatividade da planilha, incluindo cálculos, manipulação do DOM e exportação de dados.
