Projeto de Dados
Análise histórica dos campeões do Brasileirão Série A com gráficos e mapa interativo.

Este projeto analisa os campeões do Campeonato Brasileiro de Futebol Série A, utilizando dados históricos desde 1959. O objetivo é explorar os vencedores por cidade e criar visualizações interativas que mostrem os títulos ao longo do tempo.

## Conteúdo do projeto

- `campeoes_brasileirao.csv` – Dados originais dos campeões, vice, artilheiros e gols.
- `Trophy2.png` – Ícone de troféu utilizado no mapa interativo.
- `ProjetoData.ipynb` – Notebook principal com análise, gráficos e mapa interativo.
- `graficotitulos.png` – Gráfico de barras mostrando as cidades com mais títulos.
- `mapa_campeoes.html` – Mapa interativo das cidades campeãs com ícones de troféu proporcionais.

## Análises e visualizações

1. Tabela de campeões por cidade
   
   - Limpeza de dados e seleção das colunas relevantes (`Ano`, `Vencedor`).  

3. Gráfico de barras
   
   - Mostra as cidades que ganharam mais títulos.  
   - Os valores no topo das barras indicam o número de títulos.

5. Mapa interativo
   
   - Cada cidade campeã possui um ícone de troféu dourado.  
   - O tamanho do ícone é proporcional ao número de títulos.  
   - Popups mostram o nome da cidade e o número de títulos.
