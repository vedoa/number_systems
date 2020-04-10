---
title: "Appendix A"
date: 2020-04-10 18:21:56
output:
  html_document:
    keep_md: true
    code_folding: hide
    df_print: paged
    highlight: tango
    number_sections: yes
    theme: flatly
    toc: yes
    toc_depth: 2
bibliography: number_systems.bib
---

<style>

body {
text-align: justify}

</style>






# Note

This section is based in [@mendelson_number_2008, Appendix A, pp 279-280]

# Equality

In almost all mathematical theories equality is taken to be a primitive undefined relation

## Properties

__Assumption I__  $(\forall x)(x = x) \text{ (Reflexivity)}$

__Assumption II__ $(\forall x \land y)(x = x) \text{ (Reflexivity)}$

$$x = y \implies (\mathscr{A}(x,x) \implies \mathscr{A}(x,y)) \text{ (Substitutivity)}$$

- Where $\mathscr{A}(x,x)$ refers to any formula of the given theory and $\mathscr{A}(x,y)$ results from $\mathscr{A}(x,x)$ by replacing some occurrences of $x$ by $y$

    + $\mathscr{A}(x,x)$ may contain other variables in addition to $x$

# Bibliography
