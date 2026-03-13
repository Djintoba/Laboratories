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

1. Launch several different programs, learn a new presentation package and new language commands.


# Completing the lab

Let's get started with a new package. In LaTeX, you can create presentations using the beamer document class. To create slides, you can use the frame environment with the slide title as the only argument. 

![Program 1](1.png){ #fig:001 width=70% }

 
To organize information in a presentation, you can use boxes, columns, lists, and bulleted lists. 

![Program 2](2.png){ #fig:002 width=70% }

To make slide elements appear one after another, use pause. This command can be placed almost anywhere in the code. 

![Program 3](3.png){ #fig:003 width=70% }

or in a list.

![Program 4](4.png){ #fig:004 width=70% }

The uncover command allows you to precisely control when each section of a slide is displayed. This command is more flexible than the pause command. Below is an example of using the uncover command.

![Program 5](5.png){ #fig:005 width=70% }

There are many different ways to transfer the general structure of a poster into LaTeX. Here's one of them.

![Program 6](6.png){ #fig:006 width=70% }

The programs work correctly. 

# Conclusions

I became familiar with the LaTeX language and continued exploring its capabilities.



