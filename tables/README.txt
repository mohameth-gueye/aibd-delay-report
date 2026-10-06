tables/: one .tex file per table, named tab_<content>.tex.
Each file holds a complete table environment (caption, label, tabular).
A section pulls it in with \input{tables/tab_<content>}.
Labels: \label{tab:<content>}. Numbers are copied from results/*.csv of the
analysis repository and are never typed from memory.
