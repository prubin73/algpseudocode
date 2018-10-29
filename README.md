This repository contains a LyX module to facilitate use of the `algpseudocode.sty` style file, part of the `algorithmx` LaTeX package. It is available under the GPLv2 open-source license.

The module provides the following paragraph styles:

* __Algorithm__ to create an `algorithmic` environment;
* __Function__ and __EndFunction__ to enter functions;
* __Procedure__ and __EndProcedure__ to enter procedures;
* __For__ and __EndFor__ to enter for loops;
* __Loop__ and __EndLoop__ to enter indefinite loops;
* __Repeat__ and __Until__ to enter repeat loops;
* __While__ and __EndWhile__ to enter while loops;
* __If__, __Else if__, __Else__ and __EndIf__ to enter conditional statements;
* __Call__ to enter procedure calls;
* __Ensure__ and __Require__ to make assertions about algorithms;
* __Return__ to enter a return statement; and
* __State__ to enter a typical line of code.

There is also a paragraph style (corresponding to the `\Statex` command from the LaTeX package) to insert a blank, unnumbered line.

In-line comments are supported by a custom inset.

A LyX document (`pseudocode.lyx`) with some minimal instructions and examples is also provided.

This module is written for file format 66, the current format for LyX 2.3.1. You may be able to use it with (somewhat) older versions of LyX by manually editing the `Format` line in the module.

Bug reports and feature requests are welcome, using the issue tracker for the repository.

