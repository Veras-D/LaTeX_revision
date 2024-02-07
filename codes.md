# Algoritimos
```latex
\usepackage{listings}

...

\begin{lstlisting}[language=Python, caption=Exemplo de código em Python, label=lst:exemplo]
	# Código Python de exemplo
	def hello_world():
	    print("Hello, world!")
	
	hello_world()
\end{lstlisting}

...
```

Ou...

```latex
\usepackage{listings}
...
\lstinputlisting[language=Python, caption=Exemplo de código em Python, label=lst:pythoncode]{seuarquivo.py}
...
```

## Listando
```latex
\usepackage{listings}
\renewcommand{\lstlistlistingname}{Lista de Códigos} % Renomeia o título da lista de códigos
...
\lstlistoflistings % Lista de Códigos
...
```

