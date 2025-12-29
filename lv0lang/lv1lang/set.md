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
\leftrightarrow \subset(x\ y)\land\subseteq(x\ y)\neq(x\ y)
```
$`\emptyset`$
```math
\leftrightarrow =(\emptyset\ y)\forall t
```
$`\cap(\bullet\bullet)`$
```math
\leftrightarrow =(\cap(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\land \in(t\ x)\in(t\ y)
```
$`\cup(\bullet\bullet)`$
```math
\leftrightarrow =(\cup(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\lor\in(t\ x)\in(t\ y)
```
$`\sim(\bullet\bullet)`$
```math
\leftrightarrow =(\sim(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\land\in(t\ x)\in(t\ y)
```
$`\{1(\bullet)`$
```math
\leftrightarrow =(\{1(x)\ y)\forall t\leftrightarrow \in(t\ y)=(t\ x)
```
$`\{2(\bullet\bullet)`$
```math
\leftrightarrow =(\{2(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\lor =(t\ x)=(t\ y)
```
$`suc(\bullet)`$
```math
=(suc(x)\ \cup(x\ single(x)))
```
$`0`$
```math
=(0\ \emptyset)
```
$`1`$
```math
=(1\ suc(0))
```
$`pair(\bullet\bullet)`$
```math
=(\{2(x\ y)\ \{2\}(\{1(x)\ \{2(x\ y)))
```
$`\langle2(\bullet\bullet)`$
```math
=(\langle2(x\ y)\ \{2(\{2(0\ x)\ \{2(1\ y)))
```
$`\bigcup(\bullet)`$
```math
\leftrightarrow =(\bigcup(x)\ y)\forall t\leftrightarrow \in(t\ y)\exists z\land\in(t\ z)\in(z\ x)
```
$`\bigcap(\bullet)`$
```math
\leftrightarrow =(\bigcap(x)\ y)\forall t\leftrightarrow \in(t\ y)\forall z\rightarrow \in(z\ y)\in(t\ z)
```
$`power(\bullet)`$
```math
\leftrightarrow =(power(x)\ y)\forall t\leftrightarrow \in(t\ y)\subseteq(t\ y)
```
$`cartmul(\bullet\bullet)`$
```math
\leftrightarrow =(cartmul(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\exists u\exists v
\land\land \in(u\ x)\in(v\ y)=(t\ k\{2\}(u\ v))
```
$`\blacktriangleright function(\bullet)`$
```math
\begin{align}
\leftrightarrow function(f)\land&\forall t\rightarrow \in(t\ f)\exists x\exists y=(t\ k\{2\}(x\ y))\\
&\forall x\forall y\forall z\rightarrow\land\in(k\{2\}(x\ y)\ f)\in(k\{2\}(x\ z)\ f)=(y\ z)
\end{align}
```
$`dom(\bullet)`$
```math
\leftrightarrow=(dom(f)\ y)\forall t\leftrightarrow\in(t\ y)\exists z\in(k\{2\}(z\ t)\ f)
```
$`ran(\bullet)`$
```math
\leftrightarrow=(ran(f)\ y)\forall t\leftrightarrow\in(t\ y)\exists z\in(k\{2\}(t\ z)\ f)
```
$`\circ(\bullet\bullet)`$
```math
\begin{align}
\leftrightarrow =(comp(f\ g)\ h)\forall t\leftrightarrow &\in(t\ h)&\\
&\exists x\exists y\exists z \land&\land\in(k\{2\}(x\ y)\ f)\in(k\{2\}(y\ z)\ g)\\
&&=(t\ k\{2\}(x\ z))
\end{align}
```
$`inv(\bullet)`$
```math
\leftrightarrow =(inv(f)\ g)\forall t\leftrightarrow \in(t\ g)\exists x\exists y\land\in(k\{2\}(x\ y)\ f)=(t\ k\{2\}(y\ x))
```
$`restric(\bullet\bullet)`$
```math
=(restric(f\ x)\ \cap(f\ cartmul(x\ ran(f))))
```
$`app(\bullet\bullet)`$
```math
\begin{align}
\leftrightarrow=(app(f\ x)\ y)\lor&\land&\exists z\land \in(k\{2\}(x\ z)\ f)\forall u\rightarrow \in(k\{2\}(x\ u)\ f)=(u\ z)\\
&&\in(k\{2\}(x\ y)\ f)\\
&\land&\lnot\exists z\land \in(k\{2\}(x\ z)\ f)\forall u\rightarrow \in(k\{2\}(x\ u)\ f)=(u\ z)\\
&&=(y\ \emptyset)
\end{align}
```
$`map(\bullet\bullet)`$
```math
\leftrightarrow =(map(x\ y)\ z)\forall t\leftrightarrow\in(t\ z)\land\land function(t)=(dom(t)\ y)\subseteq(ran(t)\ x)
```
$`\blacktriangleright onto(\bullet\bullet)`$
```math
\leftrightarrow onto(f\ x)\land function(f)=(dom(f)\ x)
```
$`\blacktriangleright into(\bullet)`$
```math
\leftrightarrow into(f)\land function(f)\forall x\forall y\forall z\rightarrow \land\in(x\ z)\in(y\ z)=(x\ y)
```
$`\blacktriangleright bijec(\bullet\bullet)`$
```math
\leftrightarrow bijec(f\ x)\land onto(f\ x)into(f)
```
