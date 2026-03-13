---
title: "Practical scientific writing"
subtitle: "Laboratory Work No. 4"
author: "NONOGA Djintoba"
institute: "RUDN University, Moscow, Russia"
date: "February 09, 2026"
lang: en

## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text

---
# Objective of the Work

To become familiar with the LaTeX language and continue studying its capabilities.

# Task

Launch several different programs, study a new package for working with graphics and new language commands.

# Execution of Laboratory Work

Start working with a new package. To add graphics from an external source to LaTeX, we use the graphicx package, which adds the '\ includegraphics command to LaTeX.

![Program 1](1.png){ #fig:001 width=70% }

Try changing the image's height and width. LaTeX automatically scales the image to preserve its aspect ratio.

![Program 2](2.png){ #fig:002 width=70% }

We can not only change the width and height of the image but also crop it and rotate it at various angles.

![Program 3](3.png){ #fig:003 width=70% }

Graphical elements can be moved to another place in the document. This is called a floating element. Let's try implementing this in a program.

![Program 4](4.png){ #fig:004 width=70% }

Often, it is required for a figure to appear in the output exactly where it is placed in the input data. The float package allows this to be done using the H option.

![Program 5](5.png){ #fig:005 width=70% }

If we need several environments, this can be done using the trivfloat package. It provides a single command \ trivfloat for creating new types of floating environments.

![Program 6](6.png){ #fig:006 width=70% }

For LaTeX to remember a place in the document, it needs to be marked and then referenced from other places.

![Program 7](7.png){ #fig:007 width=70% }

Turn cross-references into hyperlinks using the hyperref package. It should be noted that if we place a reference outside of a chapter, it will neither display nor function.

![Program 8](8.png){ #fig:008 width=70% }

The programs work correctly.

# Conclusions

I became familiar with the LaTeX language and continued studying its capabilities.



