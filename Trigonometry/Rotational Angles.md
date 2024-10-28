
```tikz
 \begin{document} 

 \newcommand\bigangle[2][]{% 
    \draw[->,domain=0:#2,variable=\t,samples=200,>=latex,#1]
      plot ({(\t+#2)*cos(\t)/(#2)},
           {(\t+#2)*sin(\t)/(#2)}) node[right=.5cm] {$#2^\circ$}
        ;}

 \begin{tikzpicture}
 \draw [thick] ( -3,0) -- (3,0);
 \draw [thick] ( 0,-3) -- (0,3); 
 \draw [red,thick] ( 0,0) -- (600:3); 
 \bigangle[blue,dashed]{600}      
 \end{tikzpicture}
 \end{document}
```
