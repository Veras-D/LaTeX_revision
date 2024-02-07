# Inserindo Figuras

Dentro do ambiente [[LaTex com Overleaf|Inicio e de fim]], x é a largura da imagem
```latex
\begin{figure}[ht]
    \includegraphics[width=xcm]{Caminho_da_Imagem.png}
    \caption{Legenda da Imagem}
    \labal{Fig01} % opcional
    \centering % opcional
\end{figure}
```

## PARÂMETROS DA IMAGEM

- `[h]`: Coloca a figura onde ela aparece no código (aqui).
- `[t]`: Coloca a figura no topo da página.
- `[b]`: Coloca a figura na parte inferior da página.
- `[p]`: Coloca a figura em uma página separada (float page).
- `[ht]`: Tenta colocar a figura no local onde ela aparece no código (aqui) ou no topo da página, se não for possível no local atual.

## \\label{Apelido para figura}

Serve para armazenar o nome da figura e depois chama-lo pela função \\ref{Apelido para figura}

## Figura ao lado de texto
Obs.: Minipage também pode ser usado para colocar texto lado a lado
```
\begin{figure}
	\begin{minipage}[!]{0.35\linewidth}
	Texto
	\end{minipage}
	\begin{minipage}[!]{0.35\linewidth}
	\includegraphics[\width=\linewidth]{imagem2.png}\\
	\caption{Legenda}
	\end{minipage}
\end{figure}
```

## Figuras Lado a Lado
```latex
\begin{figure}
	\begin{minipage}[!]{0.35\linewidth}
	\includegraphics[\width=\linewidth]{imagem1.png}\\
	\caption{Legenda}
	\end{minipage}
	\begin{minipage}[!]{0.35\linewidth}
	\includegraphics[\width=\linewidth]{imagem2.png}\\
	\caption{Legenda}
	\end{minipage}
\end{figure}
```
