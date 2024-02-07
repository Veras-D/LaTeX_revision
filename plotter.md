# Graficos
Pacote usado é o `\usepackege{pgfplots}` 
```latex
\pfgplotsset{compat=1.18, widht=10cm}
```

## 2D
### Por Pontos
```latex
\begin{tikzpicture}
	\begin{axis}
		\addplot coordinates{
		(0,0.1) (0.1,0.2) (0.4,0.5) (1,0.52)};
	\end{axis}
\end{tikzpicture}
```
![](https://i.imgur.com/BxfG9UT.png)

### Por Equação
```latex
\begin{figure}
	\centering
	\begin{tikzpicture}
		\begin{axis}[title=Cosseno, xlabel=$x$, ylabel=$y(x) = cos(x)$, axis lines=left]
			\addplot[dominian=-4:4, green, smooth] {cos(deg(x))};
			\addlegendentry{$cos(x)$}
		\end{axis}
	\end{tikzpicture}
	\caption{Legenda}
	\label{fig:graf_01}
\end{figure}
```
![[Pasted image 20240204010404.png]]

- `addplot[onlymark]`
- Para colocar outro grafico basta colocar outros `addplot`

```latex
\begin{tikzpicture}
	\begin{axis}[Clip=false, 
	xmin=0, xmax=2.5*pi,
	xmin=-1.5, xmax=1.5,
	axis lines=meddle,
	xtick={0,pi/2,pi,3*pi/2,2*pi},
	xticklabels={$0$,$\frac{\pi}{2}$,$pi$, $\frac{3}{2}\pi$,$2\pi$},
	xticklabels style={anchor=south west},
	xmojorgrids=true,
	grid style=dashed
	]
		\addplot[dominian=0:2*pi, red, smooth] {sin(deg(x))}
		node[right, pos=0.9]{$f(x)=\sin(x)$};
		\addplot[dominian=0:2*pi, blue, smooth] {cos(deg(x))}
		node[right, pos=1]{$f(x)=\cos(x)$};
	\end{axis}
\end{tikzpicture}
```
![[Pasted image 20240204015944.png]]

### Por arquivo de texto com dados
```latex
\begin{tikzpicture}
	\begin{axis}
		\addplot+[
		only marks,
		scatter,
		max size=2.9pt]
		table[meta=ma]
		{arquivo.txt};
	\end{axis}
\end{tikzpicture}
```
![[Pasted image 20240204020752.png]]
> [!important]
> Os dados do arquivo de texto devem estar separeados por espaço

![[Pasted image 20240204020546.png]]

```latex
\begin{tikzpicture}
	\begin{axis}[scatter/classes{
	a={mark=square*,blue}
	b={mark=triangle*,red}
	c={mark=o,draw=black}}]
		\addplot[scatter,only marks,scatter scr=explicit symbolic]
		coordinates{
		(0.25,0.74) [a]
		(0.74,0.15) [b]
		(0.1,0.99) [a]
		(0.75,0.11) [b]
		(0.85,0.23) [a]
		(0.44,0.65) [c]
		(0.74,0.02) [b]
		(0.45,0.35) [c]
		(0.74,0.26) [b]
		};
	\end{axis}
\end{tikzpicture}
```
![[Pasted image 20240204022136.png]]

### Barras
```latex
\begin{tikzpicture}
	\begin{axis}[ybar stacked]
		\addplot coordinates
		{(0,0.1) (0.1,0.2) (0.4,0.5) (1,0.52)};
		\addplot coordinates
		{(0,0.1) (0.1,0.2) (0.4,0.5) (1,0.52)};
		\addplot coordinates
		{(0,0.1) (0.1,0.2) (0.4,0.5) (1,0.52)};
	\end{axis}
\end{tikzpicture}
```

## 3D
### Por Pontos
```latex
\begin{tikzpicture}
	\begin{axis}
		\addplot coordinates{
		(0,0,0) (0.1,0,2) (0.4,0,5) (1,0,52)};
	\end{axis}
\end{tikzpicture}
```
![[Captura de tela de 2024-02-04 01-17-02.png]]

### Para Superficies
```latex
\begin{figure}[hgb!]
	\centering
	\begin{tikzpicture}
		\begin{axis}[colormap/cool]
			\addplot3[surf] {x^2+y^2};
			\addlegendentry{$z=x^2+y^2$}
		\end{axis}
	\end{tikzpicture}
	\caption{Legenda}
	\label{fig:graf_01}
\end{figure}
```
![[Pasted image 20240204012910.png]]


