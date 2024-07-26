# 📊 Tags de Tabelas

Aqui estão as principais tags HTML usadas para criar e estruturar tabelas em páginas web:

## **`<table>`**
Define uma tabela. Contém todos os elementos que fazem parte da tabela, como linhas, colunas e células.

### Atributos Comuns:
- `border`: Define a largura da borda da tabela (apenas CSS moderno é recomendado para bordas e estilo).

## **`<tr>`**
Define uma linha em uma tabela. Usado dentro da tag `<table>` para criar uma nova linha.

## **`<td>`**
Define uma célula de dados em uma tabela. Usado dentro de uma linha `<tr>` para criar uma célula que contém dados.

### Atributos Comuns:
- `colspan`: Define o número de colunas que a célula deve abranger.
- `rowspan`: Define o número de linhas que a célula deve abranger.

## **`<th>`**
Define uma célula de cabeçalho em uma tabela. Usado dentro de uma linha `<tr>` para criar uma célula que contém um cabeçalho de coluna ou linha.

### Atributos Comuns:
- `colspan`: Define o número de colunas que a célula de cabeçalho deve abranger.
- `rowspan`: Define o número de linhas que a célula de cabeçalho deve abranger.

## **`<thead>`**
Define um grupo de linhas de cabeçalho em uma tabela. Geralmente usado para agrupar as linhas de cabeçalho na parte superior da tabela.

## **`<tbody>`**
Define um grupo de linhas de corpo em uma tabela. Contém as linhas com os dados da tabela e é geralmente usado para agrupar o conteúdo principal da tabela.

## **`<tfoot>`**
Define um grupo de linhas de rodapé em uma tabela. Geralmente usado para agrupar linhas que contêm informações de resumo ou totais no final da tabela.

## **`<caption>`**
Define uma legenda ou título para a tabela. Colocado diretamente após a tag `<table>` para fornecer uma descrição ou título para a tabela.

## **`<col>`**
Define propriedades comuns para uma coluna em uma tabela. Usado dentro de um grupo `<colgroup>` para aplicar estilos a colunas específicas.

### Atributos Comuns:
- `span`: Define o número de colunas que o elemento `<col>` deve abranger.

## **`<colgroup>`**
Agrupa uma ou mais tags `<col>` para aplicar propriedades de estilo a um grupo de colunas.
