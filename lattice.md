note: In the theory of lattice, logic constants "$`\lor`$" and "$`\land`$" are used for signature variables. 
So I use "$`,`$" and "$`\neg\bullet\rightarrow\bullet`$" instead.
### Lattice
$`isSup(\bullet\bullet\bullet)`$
``` math
\begin{gather}
isSup(a\ A\ x)\leftrightarrow isPoset(x),\exists B\exists\leqslant(x=\langle B\ \leqslant\rangle,\\
A\subseteq B,a\in B,\\
\forall c(c\in A\rightarrow c\leqslant a),\\
\forall d(d\in B,\forall c(c\in A\rightarrow c\leqslant d)\rightarrow a\leqslant d)
)
\end{gather}
```
$`isInf(\bullet\bullet\bullet)`$
``` math
\begin{gather}
isInf(a\ A\ x)\leftrightarrow isPoset(x),\exists B\exists\leqslant(x=\langle B\ \leqslant\rangle,\\
A\subseteq B,a\in B,\\
\forall c(c\in A\rightarrow a\leqslant c),\\
\forall d(d\in B,\forall c(c\in A\rightarrow d\leqslant c)\rightarrow d\leqslant a)
)
\end{gather}
```
$`isLatt(\bullet)`$
``` math
\begin{gather}
isLatt(x)\leftrightarrow\exists A\exists \lor\exists\land(x=\langle A,\lor\land\rangle,\\
\lor:A^2\rightarrow A,\land:A^2\rightarrow A,A\neq\varnothing\\
isCommutative(\lor,\land),isAssociative(\lor,\land),isAbsorptive(\lor,\land)
)
\end{gather}
```
$`isTice(\bullet)`$
``` math
\begin{gather}
isTice(x)\leftrightarrow\exists A\exists\leqslant(x=\langle A,\leqslant\rangle,\\
isPoset(x),A\neq\varnothing\\
\forall a\forall b\exists c\exists d(\langle a,b\rangle\in A^2\rightarrow isSup(c,\{a,b\},x),isInf(d,\{a,b\},x))
)
\end{gather}
```
$`isLattice(\bullet)`$
``` math
\begin{gather}
isLattice(x)\leftrightarrow\exists A\exists \lor\exists\land\exists\leqslant(x=\langle A,\lor\land\leqslant\rangle\\
isLatt(\langle A,\lor,\land\rangle),isTice(\langle A,\leqslant\rangle))
\end{gather}
```
$`LattToTice(\bullet)`$
``` math
\begin{gather}
lattToTice(x)=\{\langle A,\leqslant\rangle|A=x\ 0,\leqslant=\{\langle a,b\rangle|\langle a,b\rangle\in A^2,a=ax_2b\}\}
\end{gather}
```
$`ticeToLattice(\bullet)`$
``` math
\begin{gather}
ticeToLattice(x)=y\leftrightarrow \exists A\exists \lor\exists\land\exists\leqslant(y=\langle A,\lor,\land,\leqslant\rangle\\
A=x\ 0,\lor:A^2\rightarrow A,\land:A^2\rightarrow A,\leqslant=x\ 1\\
\forall a\forall b\forall c(\langle a,b\rangle\lor c\leftrightarrow isSup(c,\{a,b\},x)),\\
\forall a\forall b\forall c(\langle a,b\rangle\land c\leftrightarrow isInf(c,\{a,b\},x)))
\end{gather}
```
Definition 7
``` math
isLattice(x)\leftrightarrow \neg isLatt(x)\rightarrow isTice(x)
```
Definition 8
``` math
convertToLattice(x)=\begin{cases}
\langle x\ 0,x\ 1,x\ 2,convertToTice(x)\ 1\rangle & isLatt(x)\\
\langle x\ 0,convertToLatt(x)\ 1,convertToLatt(x)\ 2,x\ 1\rangle & isTice(x)
\end{cases}
```
