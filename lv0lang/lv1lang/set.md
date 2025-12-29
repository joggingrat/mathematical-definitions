$`\blacktriangleright \neq(\bullet\bullet)`$
```math
\leftrightarrow \neq(x\ y)\lnot=(x\ y)
```
$`\blacktriangleright \notin(\bullet\bullet)`$
```math
\leftrightarrow \notin(x\ y)\lnot\in(x\ y)
```
$`\blacktriangleright \subseteq(\bullet\bullet)`$
```math
\leftrightarrow \subseteq(x\ y)\forall t\rightarrow \in(t\ x)\in(t\ y)
```
$`\blacktriangleright \subset(\bullet\bullet)`$
```math
\leftrightarrow subset(x\ y)\land\subseteq(x\ y)\neq(x\ y)
```
$`\emptyset`$
```math
\leftrightarrow =(\emptyset\ y)\forall t
```
$`intersec(\bullet\bullet)`$
```math
\leftrightarrow =(intersect(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\land \in(t\ x)\in(t\ y)
```
$`union(\bullet\bullet)`$
```math
\leftrightarrow =(union(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\lor\in(t\ x)\in(t\ y)
```
$`compli(\bullet\bullet)`$
```math
\leftrightarrow =(compli(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\land\in(t\ x)\in(t\ y)
```
$`single(\bullet)`$
```math
\leftrightarrow =(paira(x)\ y)\forall t\leftrightarrow \in(t\ y)=(t\ x)
```
$`pair(\bullet\bullet)`$
```math
\leftrightarrow =(pairb(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\lor =(t\ x)=(t\ y)
```
$`suc(\bullet)`$
```math
=(suc(x)\ union(x\ single(x)))
```
$`0`$
```math
=(0\ \emptyset)
```
$`1`$
```math
=(1\ suc(0))
```
$`kpair(\bullet\bullet)`$
```math
=(kpair(x\ y)\ pair(single(x)\ pair(x\ y)))
```
$`tuple(\bullet\bullet)`$
```math
=(tuple(x\ y)\ pair(kpair(0\ x)\ kpair(1\ y)))
```
$`sum(\bullet)`$
```math
\leftrightarrow =(sum(x)\ y)\forall t\leftrightarrow \in(t\ y)\exists z\land\in(t\ z)\in(z\ x)
```
$`intersection(\bullet)`$
```math
\leftrightarrow =(intersection(x)\ y)\forall t\leftrightarrow \in(t\ y)\forall z\rightarrow \in(z\ y)\in(t\ z)
```
$`power(\bullet)`$
```math
\leftrightarrow =(power(x)\ y)\forall t\leftrightarrow \in(t\ y)\subseteq(t\ y)
```
$`cartmul(\bullet\bullet)`$
```math
\leftrightarrow =(cartmul(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\exists u\exists v
\land\land \in(u\ x)\in(v\ y)=(t\ kpair(u\ v))
```
$`\blacktriangleright function(\bullet)`$
```math
\begin{align}
\leftrightarrow function(f)\land&\forall t\rightarrow \in(t\ f)\exists x\exists y=(t\ kpair(x\ y))\\
&\forall x\forall y\forall z\rightarrow\land\in(kpair(x\ y)\ f)\in(kpair(x\ z)\ f)=(y\ z)
\end{align}
```
$`map(x\ y)`$
```math
\leftrightarrow =(map)
```
