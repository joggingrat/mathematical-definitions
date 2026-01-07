$`\leftrightarrow \neq(x\ y)\lnot=(x\ y)`$\
$`\leftrightarrow \notin(x\ y)\lnot\in(x\ y)`$\
$`\leftrightarrow \subseteq(x\ y)\forall t\rightarrow\in(t\ x)\in(t\ y)`$\
$`\leftrightarrow \subset(x\ y)\land\subseteq(x\ y)\neq(x\ y)`$\
$`\leftrightarrow =(\emptyset\ y)\forall t\notin(t\ \emptyset)`$\
$`\leftrightarrow =(\cap(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\land\in(t\ x)\in(t\ y)`$\
$`\leftrightarrow =(\cup(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\lor\in(t\ x)\in(t\ y)`$\
$`\leftrightarrow =(\sim(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\land\in(t\ x)\notin(t\ y)`$\
$`\leftrightarrow =(\bigcap(x)\ y)\land\rightarrow\neq(x\ \emptyset)\forall t\leftrightarrow\in(t\ y)\forall z\rightarrow\in(z\ x)\in(t\ z)\rightarrow=(x\ \emptyset)=(y\ \emptyset)`$\
$`\leftrightarrow =(\bigcup(x)\ y)\forall t\leftrightarrow \in(t\ y)\exists z\land\in(t\ z)\in(z\ x)`$\
$`\leftrightarrow =(power(x)\ y)\forall t\leftrightarrow\in(t\ y)\subseteq(t\ x)`$\
$`\leftrightarrow =(pair(x\ y)\ z)\forall t\leftrightarrow\in(t\ z)\land=(t\ x)=(t\ y)`$\
$`=(the(x)\ pair(x\ x))`$\
$`=(tuple(x\ y)\ pair(the(x)\ pair(x\ y))`$\
$`\leftrightarrow =(\times(x\ y)\ z)\forall t\leftrightarrow\in(t\ z)\exists u\exists v\land\land=(t\ tuple(u\ v))\in(u\ x)\in(y\ v)`$\
$`\leftrightarrow =(dom(x)\ y)\forall t\leftrightarrow \in(t\ y)\exists z\in(tuple(t\ z)\ y)`$\
$`\leftrightarrow =(ran(x)\ y)\forall t\leftrightarrow \in(t\ y)\exists z\in(tuple(z\ t)\ y)`$\
$`=(\upharpoonright(x\ y)\cap(x\ \times(y\ ran(x))))`$\
$`\leftrightarrow =(\circ(x\ y)\ z)\forall t\leftrightarrow \in(t\ z)\exists u\exists v\exists w\land\land\in(tuple(u\ v)\ x)=(t\ tuple(v\ u))`$\
$`\leftrightarrow RELATION(x)\forall t\rightarrow\in(t\ x)\exists y\exists z=(t\ tuple(y\ z))`$\
$`\leftrightarrow FUNCTION(x)\land RELATION(x)\forall u\forall v\forall w\rightarrow \land\in(tuple(u\ v)\ x)\in(tuple(u\ w)\ x)\in(tuple(u\ w)\ x)=(v\ w)`$\
$`\leftrightarrow MAP(x\ y\ z)\land\land FUNCTION(x)=(dom(x)\ y)\subseteq (ran(x)\ z)`$\
$`\leftrightarrow INTO(x)\land FUNCTION(x)\forall u\forall v\forall w\rightarrow \land\in(tuple(u\ w)\ x)=(u\ v)`$\
$`\leftrightarrow ONTO(x\ y)\land FUNCTION(x)=(ran(x) y)`$\
$`\leftrightarrow BIJECT(x\ y)\land INTO(x)ONTO(x\ y)`$\
$`\leftrightarrow =(map(x\ y)\ z)\forall t\leftrightarrow\in(t\ z)\land\land FUNCTION(t)=(dom(z)\ x)\subseteq(ran(z)\ y)`$\
$`\leftrightarrow =(app(x\ y)\ z)\land\rightarrow FUNCTION(x)\in(tuple(y\ z)\ x)\rightarrow\lnot FUNCTION(x)=(z\ \emptyset)`$\
$`\leftrightarrow =(\lambda(x\ y)\ z)forall t\in(t\ y)\exists u\exists v\land=(y\ app(u\ v))\in(v\ x)`$\
$`\leftrightarrow ORDINAL(x)\land\rightarrow\forall t\in(t\ x)\subseteq(t\ x)\forall y\forall z\rightarrow \land\neq(y\ z)\in(y\ x)\in(z\ x)\lor\in(y\ z)\in(z\ y)`$\
$`\leftrightarrow NATURAL(x)\land ORDINAL(x)\forall y\rightarrow\land\subseteq(y\ x)\neq(y\ \emptyset)\exists z\land\in(z\ y)\forall t\rightarrow\in(t\ y)\lnot\in(z\ t)`$\
$`\leftrightarrow =(\omega\ y)\forall t\leftrightarrow \in(t\ y)NATURAL(t)`$\
$`=(suc(x)\ \cup(x\ the(x)))`$\
$`=(0\ \emptyset)`$\
$`=(1\ suc(0))`$\
$`=(2\ suc(1))`$\
$`=(3\ suc(2))`$\
$`=(4\ suc(3))`$\
$`=(5\ suc(4))`$\
$`=(6\ suc(5))`$\
$`=(7\ suc(6))`$\
$`=(8\ suc(7))`$\
$`=(9\ suc(8))`$\
$`=(double(x\ y)\ pair(tuple(0\ x)\ tuple(1\ y)))`$\
$`=(triple(x\ y\ z)\ \cup(double(x\ y)\ tuple(2\ z)))`$\
$`=(quad(x\ y\ z\ t)\ \cup(triple(x\ y\ z)\ tuple(3\ t)))`$\
$`=(quint(x\ y\ z\ t\ u)\ \cup(quad(x\ y\ z\ t)\ tuple(4\ u)))`$\
$`=(sext(x\ y\ z\ t\ u\ v)\ \cup(quint(x\ y\ z\ t\ u)\ tuple(5\ v)))`$\
$`=(sept(x\ y\ z\ t\ u\ v\ w)\ \cup(sext(x\ y\ z\ t\ u\ v)\ tuple(6\ w)))`$\
$`=(oct(x\ y\ z\ t\ u\ v\ w\ a)\ \cup(sept(x\ y\ z\ t\ u\ v\ w)\ tuple(7\ a)))`$\
$`=(non(x\ y\ z\ t\ u\ v\ w\ a\ b)\ \cup(oct(x\ y\ z\ t\ u\ v\ w\ a)\ tuple(8\ b)))`$\
$`=(dec(x\ y\ z\ t\ u\ v\ w\ a\ b\ c)\ \cup(non(x\ y\ z\ t\ u\ v\ w\ a\ b)\ tuple(9\ c)))`$\
$`leftrightarrow \approx(x\ y)\exists z\land BIJECT(z\ y)=(dom(z)\ x)`$\
$`\leftrightarrow \preceq(x\ y)\exists z\land BIJECT(z\ y)=(dom(z)\ x)`$\
$`\leftrightarrow \prec(x\ y)\land\preceq(x\ y)\lnot\approx(x\ y)`$\
$`\leftrightarrow CARDINAL(x)\land ORDINAL(x)\forall y\rightarrow \land ORDINAL(y)\approx(x\ y)\lor\in(x\ y)=(x\ y)`$\
$`\leftrightarrow =(\kappa(x)\ y)\land\approx(x\ y)CARDINAL(y)`$\
$`\leftrightarrow=(next(x)\ y)\land\rightarrow\lnot ORDINAL(x)=(y\ \emptyset)\rightarrow ORDINAL(y)\prec(x\ y)\forall z\rightarrow\land ORDINAL(z)\prec(x\ z)\lor=(z\ y)<(y\ z)`$\
$`\leftrightarrow =(\lambda(x)\ y)\land\rightarrow\lnot ORDINAL(x)=(y\ \emptyset)\rightarrow ORDINAL(x)\exists F\land\and\land\land\land MAP(F\ suc(x)\ ran(F))=(app(F\ 0)\ \omega)\forall z\rightarrow\land ORDINAL(z)\in(suc(z)\ dom(F))=(app(F\ suc(z))next(app(F\ z)))\forall z\rightarrow\land LIMORD(z)\in(z\ dom(f))=(app(F\ z)\lor(\lambda(z\ F)))=(y\ qpp(F\ x))`$
