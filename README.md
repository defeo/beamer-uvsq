beamer-uvsq
===========

UVSQ beamer template

Dependencies
------------
- fontenc
- uop (optima fonts)
- concmath (for mathematics)
- trajan (trajan font for title page)


Usage
-----

```latex
\documentclass{beamer}

\mode<presentation>{
  \usetheme{uvsq}
}

\begin{document}

% The beamer template should do this automatically for the title page,
% but I haven't managed to do it yet
\setbeamertemplate{navigation symbols}{}
\frame[plain]{\titlepage}

\end{document}

```
