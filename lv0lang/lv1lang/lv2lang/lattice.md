note: In the theory of lattice, logic constants "$`\lor`$" and "$`\land`$" are used for signature variables. 
So I use "$`,`$" and "$`\neg\bullet\rightarrow\bullet`$" instead.
### Lattice
Definition 1
``` math
\begin{gather}
isSup(a,A,x)\leftrightarrow isPoset(x),\exists B\exists\leqslant(x=\langle B,\leqslant\rangle,\\
A\subseteq B,a\in B,\\
\forall c(c\in A\rightarrow c\leqslant a),\\
\forall d(d\in B,\forall c(c\in A\rightarrow c\leqslant d)\rightarrow a\leqslant d)
)
\end{gather}
```
Definition 2
``` math
\begin{gather}
isInf(a,A,x)\leftrightarrow isPoset(x),\exists B\exists\leqslant(x=\langle B,\leqslant\rangle,\\
A\subseteq B,a\in B,\\
\forall c(c\in A\rightarrow a\leqslant c),\\
\forall d(d\in B,\forall c(c\in A\rightarrow d\leqslant c)\rightarrow d\leqslant a)
)
\end{gather}
```
Definition 3
``` math
\begin{gather}
isLatt(x)\leftrightarrow\exists A\exists \lor\exists\land(x=\langle A,\lor\land\rangle,\\
\lor:A^2\rightarrow A,\land:A^2\rightarrow A,\\
isComm(\lor,\land),isAsso(\lor,\land),isIdem(\lor,\land),isAbso(\lor,\land)
)
\end{gather}
```
Definition 4
``` math
\begin{gather}
isIce(x)\leftrightarrow\exists A\exists\leqslant(x=\langle A,\leqslant\rangle,\\
isPoset(x),\\
\forall a\forall b\exists c\exists d(\langle a,b\rangle\in A^2\rightarrow isSup(c,\{a,b\},x),isInf(d,\{a,b\},x))
)
\end{gather}
```
Definition 5
``` math
\begin{gather}
ice(x)=\{\langle A,\leqslant\rangle|A=x\ 0,\leqslant=\{\langle a,b\rangle|\langle a,b\rangle\in A^2,a=ax_2b\}\}
\end{gather}
```
Definition 6
``` math
\begin{gather}
latt(x)=y\leftrightarrow \exists A\exists \lor\exists\land(y=\langle A,\lor,\land\rangle\\
A=x\ 0,\lor:A^2\rightarrow A,\land:A^2\rightarrow A,\\
\forall a\forall b\forall c(\langle a,b\rangle\lor c\leftrightarrow isSup(c,\{a,b\},x)),\\
\forall a\forall b\forall c(\langle a,b\rangle\land c\leftrightarrow isInf(c,\{a,b\},x)))
\end{gather}
```
Definition 7
``` math
isLattice(x)\leftrightarrow \neg isLatt(x)\rightarrow isIce(x)
```
Definition 8
``` math
lattice(x)=\begin{cases}
\langle x\ 0,x\ 1,x\ 2,ice(x)\ 1\rangle & isLatt(x)\\
\langle x\ 0,latt(x)\ 1,latt(x)\ 2,x\ 1\rangle & isIce(x)\\
\emptyset & \neg isLattice(x)
\end{cases}
```
