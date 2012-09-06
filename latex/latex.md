# Latex
This file would show you some useful tags in latex. Maybe would split them into sevral different files in the furture.

## spacing
	\usepackage{setspace}
	\onehalfspacing
	\doublespacing
  
## paragraph
When you are trying to use the \begin{paragraph} tag, be careful, you must put something directly after it.
Or it would not be compiled. So use
	\begin{paragraph}{paraname}
If you want to leave the name of paragraph there and start a new line to write something, use this
	\flushleft
You can also use `\flushright` or `\center` to do it.

## eqref
Before you use the `\eqref{labelName}` to refer some equation,
	\usepackage{amsmath}

## aligned
Use this when you want to align sevral equations to their equal signs.

## listings
Use this to write your code? I don't think it's better.
	\usepackage{listings}
	\begin{lstlisting}
	\end{lstlisting}

## enumerate
When you want to change the pattern of the enumerator
	\usepackage{enumerate}
	\begin{enumerate}[pattern]
	\end{enumerate}

## because
	\usepackage{asmsymb}
	\because
	\therefore
You can only use these symbols within math mode.


