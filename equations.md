# Matemática

## Matrizes
```latex
$
\left[\begin{array}{cc} % Cada "C" aumenta a escala da matrix {cc} é uma matrix 2X2
	a & b\\
	c & d
\end{array}\right]
$
```
Saída:
$$
\left[\begin{array}{cc}
	a & b\\
	c & d
\end{array}\right] = 0
$$
## Sistemas de Equação
```latex
$
\left\{\begin{array}{ccccc}
	a & + & b & = & 10\\
	a & - & b & = & 8
\end{array}\right.
$
```
Saída:
$$
\left\{\begin{array}{ccccc}
	a & + & b & = & 10\\
	a & - & b & = & 8
\end{array}\right.
$$
## Equações via \\begin{}
**Nota: Esse é o principal meio de inserir equações, visto que é apenas por ele que é possivel inserir legenda e lebal.**
```latex
\begin{equation} 
y=x+1
\end{equation}
```
Saída:

![image](https://github.com/Veras-D/LaTeX_revision/assets/110254550/710e89aa-78c4-4190-9cd3-43050db98e29)


## Elementos Matemático
### Multiplicação 1

```Latex
\cdot
```
Saída:
$x\cdot{}y$
### Multiplicação 2

```latex
\times
```
Saída:
$x\times{}y$
### Divisão
```Latex
\div
```
Saída:
$\div$

### Diferente
```latex
a \neq b
```
Saida:
$$a \neq b$$

### Pontos
#### Pontos 1
```latex
\dots
```
Saída:
$$\dots$$

#### Pontos 2
```latex
\ldot
```
Saída:
$$\ldots$$
## Fração
### Opção 1
```latex
\frac{Numerador}{Denominador}
```
Saída:
$\frac{x}{y}$
### Opção 2
```latex
\dfrac{Numerador}{Denominador}
```
Saída:
$\dfrac{x}{y}$
## Integral
```latex
\displaystale\int_{0}^{1} x^2 \, dx = \frac{1}{3} 
```
Saída:
$$\displaystyle\int_{0}^{1} x^2 \, dx = \frac{1}{3}$$
## Somatório
```latex
\sum_{i=1}^{n} a_i = a_1 + a_2 + \dots + a_n
```
Saída:
$$\sum_{i=1}^{n} a_i = a_1 + a_2 + \dots + a_n$$
## Raiz
```latex
\sqrt[Potencia da Raiz]{Expressão}
```

Saída:
$\sqrt[3]{X+1}$

## Limite
```latex
\displaystyle\lim_{x\rightarrow 0}f(x)
```
Saída:
$$\displaystyle\lim_{x\rightarrow 0}f(x)$$

## Letras Gregas
| Letra Grega | Nome (maiúscula) | Nome (minúscula) | Comando LaTeX (maiúscula) | Comando LaTeX (minúscula) | No Ambiente LaTeX (maiúscula) | No Ambiente LaTeX (minúscula) |
|--------------|-------------------|-------------------|----------------------------|---------------------------|------------------------|-----------------------|
| Α            | Alpha             | alpha             | $$-$$                      | \alpha                    | $$-$$                  | $$\alpha$$            |
| Β            | Beta              | beta              | $$-$$                      | \beta                     | $$-$$                  | $$\beta$$             |
| Γ            | Gamma             | gamma             | \Gamma                     | \gamma                    | $$\Gamma$$             | $$\gamma$$            |
| Δ            | Delta             | delta             | \Delta                     | \delta                    | $$\Delta$$             | $$\delta$$            |
| Ε            | Epsilon           | epsilon           | $$-$$                      | \epsilon                  | $$-$$                  | $$\epsilon$$          |
| Ε            | Epsilon           | epsilon           | $$-$$                      | \varepsilon               | $$-$$                  | $$\varepsilon$$       |
| Ζ            | Zeta              | zeta              | $$-$$                      | \zeta                     | $$-$$                  | $$\zeta$$             |
| Η            | Eta               | eta               | $$-$$                      | \eta                      | $$-$$                  | $$\eta$$              |
| Θ            | Theta             | theta             | \Theta                     | \theta                    | $$\Theta$$             | $$\theta$$            |
| Ι            | Iota              | iota              | $$-$$                      | \iota                     | $$-$$                  | $$\iota$$             |
| Κ            | Kappa             | kappa             | $$-$$                      | \kappa                    | $$-$$                  | $$\kappa$$            |
| Λ            | Lambda            | lambda            | \Lambda                    | \lambda                   | $$\Lambda$$            | $$\lambda$$           |
| Μ            | Mu                | mu                | $$-$$                      | \mu                       | $$-$$                  | $$\mu$$               |
| Ν            | Nu                | nu                | $$-$$                      | \nu                       | $$-$$                  | $$\nu$$               |
| Ξ            | Xi                | xi                | \Xi                        | \xi                       | $$\Xi$$                | $$\xi$$               |
| Ο            | Omicron           | omicron           | $$-$$                      | \omicron                  | $$-$$                  | $$\omicron$$          |
| Π            | Pi                | pi                | \Pi                        | \pi                       | $$\Pi$$                | $$\pi$$               |
| Ρ            | Rho               | rho               | $$-$$                      | \rho                      | $$-$$                  | $$\rho$$              |
| Σ            | Sigma             | sigma             | \Sigma                     | \sigma                    | $$\Sigma$$             | $$\sigma$$            |
| Τ            | Tau               | tau               | $$-$$                      | \tau                      | $$-$$                  | $$\tau$$              |
| Υ            | Upsilon           | upsilon           | \Upsilon                   | \upsilon                  | $$\Upsilon$$           | $$\upsilon$$          |
| Φ            | Phi               | phi               | \Phi                       | \phi                      | $$\Phi$$               | $$\phi$$              |
| Χ            | Chi               | chi               | $$-$$                      | \chi                      | $$-$$                  | $$\chi$$              |
| Ψ            | Psi               | psi               | \Psi                       | \psi                      | $$\Psi$$               | $$\psi$$              |
| Ω            | Omega             | omega             | \Omega                     | \omega                    | $$\Omega$$             | $$\omega$$            |




# Outros Exemplos


| nome | código | equação |
| ---- | ---- | ---- |
| Equação da Pressão dinâmica | `q_{\infty}= \frac{1}{2}\rho_{\infty}V_{\infty}^{2}` | $$q_{\infty}= \frac{1}{2}\rho_{\infty}V_{\infty}^{2}$$ |
| Equação Geral da Transferencia de Calor em Aletas | `\dot{E}_e+\dot{E}_g-\dot{E}_s=\dot{E}_{acu}=\rho c_p\frac{\partial T}{\partial t} \rightarrow \frac{\partial}{\partial x}\left(A_{t} \frac{\partial T}{\partial x}\right)-\frac{h}{k}\frac{dA_{s}}{dx} \left(T-T_{\infty}\right)=0` | ![image](https://github.com/Veras-D/LaTeX_revision/assets/110254550/20aa4bf3-9384-4093-8778-e91df4e1a384) |
| Equação da trafenrencia de Calor na extremidade da Aleta | `q_{cond}=\sqrt{hPkA_t}\theta_b\frac{\cosh[m(L-x)]+(h/mk)\sinh[m(L-x)]}{\cosh[mL]+(h/mk)\sinh[mL]}` | $$q_{cond}=\sqrt{hPkA_t}\theta_b\frac{\cosh[m(L-x)]+(h/mk)\sinh[m(L-x)]}{\cosh[mL]+(h/mk)\sinh[mL]}$$ |
| Equação Geral da Transferencia de Calor em Regime Transiente | `t=\frac{\rho \forall c}{4\varepsilon A_{s}\sigma T_{v}^{3}}\left\{\ln\left\|\frac{T_{v}+T}{T_{v}-T}\right\|-\ln\left\|\frac{T_{v}+T_{i}}{T_{v}-T_{i}}\right\|+2\left[\tan^{-1}\left(\frac{T}{T_{v}}\right)-\tan^{-1}\left(\frac{T_{i}}{T_{v}}\right)\right]\right\}` | ![image](https://github.com/Veras-D/LaTeX_revision/assets/110254550/b28283ea-a50b-44dc-8bb2-c627deb0f8dc) |
| Equação Geral da Transferencia de Calor | `\frac{\partial^{2} T}{\partial x^{2}}+\frac{\partial^{2} T}{\partial y^{2}}+\frac{\partial^{2} T}{\partial z^{2}}+\frac{q}{k}=\frac{1}{\alpha}\frac{\partial T}{\partial t}` | $$\frac{\partial^{2} T}{\partial x^{2}}+\frac{\partial^{2} T}{\partial y^{2}}+\frac{\partial^{2} T}{\partial z^{2}}+\frac{q}{k}=\frac{1}{\alpha}\frac{\partial T}{\partial t}$$ |


