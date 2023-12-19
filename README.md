# Probability Exam Cheat Sheet

## Description
Some formulas used in the probability exam.
The files come without any warranty.

## Usage
Change the .tex file and compile it.
Each block is made by its content and its header, if you want to change a block just change both.
To make new blocks just copy one and change it.

That's a block:
```latex
%------------ ABlock Content ---------------
\begin{tikzpicture}
\node [mybox] (box){%
    \begin{minipage}{0.3\textwidth}
    Some stuff
    \end{minipage}
};
%------------ Block Header ---------------------
\node[fancytitle, right=10pt] at (box.north west) {Block Header};
\end{tikzpicture}
```

## Credits
The template is taken from Drew Ulick "130 Cheat Sheet" (https://www.overleaf.com/articles/130-cheat-sheet/ntwtkmpxmgrp).
