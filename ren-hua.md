# ren hua
"人话($`\mathrm{r\acute{e}n\ hu\grave{a}}`$)", translated directly into English is "human language". In the context of a chinese people accusing another not speaking human language, He means that there are little consensus between them, so it feels like he is talking to another species. To avoid this, I define the formal language renhua, which after translation, become an extension by definition of ZFC.

# syntax of ren hua
\<white space\> can be interpreted as ASCII 32, a `\quad` in latex, or simply a gap in writing.
- \<term\>::=\<variable\>|\<func0a\>|\<func1a\>(\<term\>)|\<funct2a\>(\<term\>,\<term\>)|\<func3a\>(\<term\>,\<term\>,\<term\>)|$`\langle`$\<term list\>$`\rangle`$|$`\{`$\<term list\>$`\}`$|(\<term\>\<apply\>)|$`|`$\<term\>$`|`$
- \<term list\>::=\<term\>,\<term list\>|\<empty string\>
- \<apply\>::=\<space\>
- \<atom\>::=$`\top`$|$`\bot`$|\<predicate1a\>(\<term\>)|\<predicate2a\>(\<term\>,\<term\>)|\<predicate3a\>(\<term\>,\<term\>,\<term\>)|\<term\>$`\in`$\<term\>|\<term\>=\<term\>|\<term\>$`:`$\<term\>$`\rightarrow`$\<term\>
- \<wff\>::=\<atom\>|$`\exists`$\<variable\>\<atom\>|$`\exists`$\<variable\>(\<wff\>)|$`\forall`$\<variable\>(\<wff\>)|$`\forall`$\<variable\>\<atom\>|$`\lnot`$\<wff\>|\<wff\>,\<wff\>|\<wff\>$`\lor`$\<wff\>|\<wff\>$`\rightarrow`$\<wff\>|\<wff\>$`\leftrightarrow`$\<wff\>|(\<wff\>$`\lor`$\<wff\>)|(\<wff\>$`\rightarrow`$\<wff\>)$`|`$(\<wff\>$`\leftrightarrow`$\<wff\>)
- 
# semantic of ren hua
