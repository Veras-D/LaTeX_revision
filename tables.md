# Tabelas Em LaTeX
## Geral
Exemplo:
```latex
\begin{table}[!]
\centering
\begin{tabular}{c|c} % {l|l|c} ou {c|c|c} ou {r|r|r} ou outras combinações, | são as barras verticais
	\hline
	Coluna 1 & Coluna 2 \\
	\hline
	Linha 2 & Linha 2
\end{tabular}
\caption{Legenda}
\label{tab: Minha Tabela}
\end{table}
```
Saída:
![](https://i.imgur.com/AP9cCpq.png)

- l é alinhado a esquerda 
- c é centralizado
- r é alinhado a direita
- `\hline` gera uma linha vertical entre as linhas
- `|` (Barra vertical) Coloca uma barra vertical entre as colunas
## Parâmetros do \\begin{table}[ ]

- `[h]`: Coloque a tabela onde ela aparece no código (aqui).
- `[t]`: Coloque a tabela no topo da página.
- `[b]`: Coloque a tabela na parte inferior da página.
- `[p]`: Coloque a tabela em uma página separada (float page).
- `[!]`: Força LaTeX a tentar colocar a tabela no local onde ela aparece no código, mesmo que o algoritmo normal de posicionamento não concorde.
- Comum ultilizar `\begin{table}[ht]`

