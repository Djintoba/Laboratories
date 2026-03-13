---
title: "Laboratory Work No. 3"
subtitle: "Practical scientific writing"
author: "Nonoga Djintoba"
lang: en-US
mainfont: "Times New Roman"

## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

## Objective
In this laboratory work, we consider the mathematical mode of LaTeX, ways to input and display formulas, extensions provided by the amsmath package, as well as ways to change fonts in mathematical expressions.

## Task
Use the Latex program to write some formulas and mathematical equations.

## Laboratory Work
First, let's look at how to write a mathematical formula. The entire expression must be enclosed in quotes.

![Example 1](1.png)

To display superscripts and subscripts, use the ^ and _ symbols respectively, and to display Greek letters, use the \ symbol followed by the letter name, as in the example.

![Example 2](2.png)

To display an integral, we use the command and fill in the integral bounds as the lower and upper index earlier.

![Example 3](3.png)

Now let's look at more complex commands. Here we used the new amsmath package. We will use it to write a program that adds text to formulas. With this package we can display matrices in brackets, as shown in the examples below.

![Example 4](4.png)

The amsmath package allows numbering formulas in the document and aligning text. Standard LaTeX offers two ways to highlight mathematical symbols in bold. To highlight the entire expression in bold, use the \ mathbf command before entering it. The \ mathbf command can also be used to bold individual letters or words. See the screenshot for illustration.

![Example 5](5.png)

The mathtools package loads amsmath and adds several additional features, such as variants of amsmath matrix environments that allow setting column alignment. You can change the alignment simply by changing the letter to r or l at the beginning of the command.

![Example 6](6.png)

A small example of additional fonts.

![Example 7](7.png)

## Conclusions
I became acquainted with the LaTeX language and continued to study its capabilities.