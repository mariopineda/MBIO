```tikz
\begin{document} 
\begin{tikzpicture} 
% Define the coordinates of the triangle 
\coordinate [label=left:A] (A) at (0,0); 
\coordinate [label=right:B] (B) at (5,0); 
\coordinate [label=above:C] (C) at (3,4); 
% Draw the sides of the triangle 
\draw [thick] (A) -- (B) -- (C) -- cycle; 
% Label the sides 
\draw (A) -- node[below] {$c$} (B); 
\draw (B) -- node[right] {$a$} (C); 
\draw (C) -- node[left] {$b$} (A); 
% Label the angles 
\draw (0.6,0) arc (0:53.13:0.6) node[midway, right] {$\gamma$}; 
\draw (3.9,0.4) arc (173.13:180:0.6) node[midway, above] {$\beta$}; 
\draw (2.35,3.2) arc (-28.87:0:0.6) node[midway, right] {$\alpha$}; 
% Label the vertices 
\node [below left] at (A) {A}; 
\node [below right] at (B) {B}; 
\node [above] at (C) {C}; 
\end{tikzpicture} 
\end{document}
```