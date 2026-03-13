---
title: "Practical scientific writing"
subtitle: "Laboratory Work No. 6"
author: "NONOGA Djintoba"
institute: "RUDN University, Moscow, Russia"
date: "February 11, 2026"
lang: en

## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Purpose of the work

To become familiar with the LaTeX language and further explore its capabilities. 

# Task

 Run several different programs, learn a new graphics package and new language commands.

# Completing the Lab

Let's start working with the new package. Reference databases are commonly referred to as "BibTeX files," and they have the extension .bib. They contain one or more records, one for each reference, and each record has several fields. Let's create a file with this extension and populate it. 

![Program 1](b.png){ #fig:001 width=70% }

 
We'll use the natbib package, which allows us to create various citation types and offers a variety of styles. The basic structure of our input is shown in this example. 

![Program 2](1.png){ #fig:002 width=70% }

The biblatex package works slightly differently than natbib: we select databases in the preamble but output them in the main body of the document. Several new commands are available for this. We'll demonstrate this with an example.

![Program 3](2.png){ #fig:003 width=70% }

Although both BibTeX and biblatex receive input in the form of BibTeX files and can produce structurally similar output in a document, they use completely different methods to achieve this result. This means there are some differences between the two approaches that can help you choose the most appropriate option.

The programs work correctly. 

# Conclusion

I became familiar with the LaTeX language and continued exploring its capabilities.



