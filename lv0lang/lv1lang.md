# Syntax of lv1lang
## Tokens
$`\mathrm{VARIABLE}::=`$$` \langle\mathrm{lower\ case}\rangle|\langle\mathrm{upper\ case}\rangle|\langle\mathrm{a\ sequence}\rangle`$\
$`\langle\mathrm{lower\ case}\rangle::=`$$`a|b|c|d|e|f|g|h|i|j|k|l|m|n|o|p|q|r|s|t|u|v|w|x|y|z`$\
$`\langle\mathrm{upper\ case}\rangle::=`$$`A|B|C|D|E|F|G|H|I|J|K|L|M|N|O|P|Q|R|S|T|U|V|W|X|Y|Z`$\
$`\langle\mathrm{a\ sequence}\rangle::=`$$`a|a\langle\mathrm{a\ sequence}\rangle`$\
$`\mathrm{0ARY\ FUNCTION}::=`$\
$`\mathrm{1ARY\ FUNCTION}::=`$\
$`\mathrm{2ARY\ FUNCTION}::=`$\
$`\mathrm{3ARY\ FUNCTION}::=`$\
$`\mathrm{0ARY\ PREDICATE}::=`$$`\top|\bot`$\
$`\mathrm{1ARY\ PREDICATE}::=`$\
$`\mathrm{2ARY\ PERDICATE}::=`$$`\in|`$\
$`\mathrm{3ARY\ PREDICATE}::=`$
## Formula
$`\blacktriangleright\langle\mathrm{formula}\rangle::=`$$`\langle\mathrm{atom}\rangle|`$$`\lnot\langle\mathrm{formula}\rangle|`$$`\land\langle\mathrm{formula}\rangle\langle\mathrm{formula}\rangle|`$$`\lor\langle\mathrm{formula}\rangle\langle\mathrm{formula}\rangle|`$$`\rightarrow\langle\mathrm{formula}\rangle\langle\mathrm{formula}\rangle|`$$`\leftrightarrow\langle\mathrm{formula}\rangle\langle\mathrm{formula}\rangle|`$$`\forall\mathrm{VARIABLE}\langle\mathrm{formula}\rangle|`$$`\exists\mathrm{VARIABLE}\langle\mathrm{formula}\rangle|`$\
$`\blacktriangleright\langle atom\rangle::=`$$`\mathrm{0ARY\ PREDICATE}|`$$`\mathrm{1ARY\ PREDICATE}(\langle\mathrm{term}\rangle)|`$$`\mathrm{2ARY\ PREDICATE}(\langle\mathrm{term}\rangle\langle\mathrm{term}\rangle)|`$$`\mathrm{3ARY\ PREDICATE}(\langle\mathrm{term}\rangle\langle\mathrm{term}\rangle\langle\mathrm{term}\rangle)`$\
$`\blacktriangleright \langle\mathrm{term}\rangle::=`$$`\mathrm{VARIABLE}|`$$`\mathrm{0ARY\ FUNCTION}|`$$`\mathrm{1ARY\ FUNCTION}(\langle\mathrm{term}\rangle)|`$$`\mathrm{2ARY\ FUNCTION}(\langle\mathrm{term}\rangle\langle\mathrm{term}\rangle)|`$$`\mathrm{3ARY\ FUNCTION}(\langle\mathrm{term}\rangle\langle\mathrm{term}\rangle\langle\mathrm{term}\rangle)`$
## Provable formula

# Semantics of lv1lang
lv1lang doesn't have a fixed semantics. It might say something about the real world, but eventually it's up to you how to
interpret these formulas and provable formulas.
