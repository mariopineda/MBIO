```tikz
\usepackage{pgfplots}
\begin{document}
\begin{tikzpicture}[scale=1.5]
  \begin{axis} [axis lines=center]
    \addplot [domain=-3:3, smooth, thick] { x^3 - 5*x };
  \end{axis}
\end{tikzpicture}
\end{document}
```


```tikz
\usepackage{pgfplots}
\begin{document}
\begin{tikzpicture}[scale=1.5]
  \begin{axis} [grid, xtick = {-360,-270,...,360}]
    \addplot [domain=-360:360, samples=100, thick, color=blue] { sin(x) };
  \end{axis}
\end{tikzpicture}
\end{document}
```