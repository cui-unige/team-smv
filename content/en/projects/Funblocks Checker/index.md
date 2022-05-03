---
title: "Funblocks Checker"
weight: 1
resources:
    - src: pipeline.png
      params:
          weight: -100
---

Master thesis  
Author: Marvin Fourastié  
Language: English  
Document available [here](/team-smv/projects/Marvin_s_master_thesis.pdf)

## Abstract 

The teaching of computer science has become essential in the majority of educational programs. Therefore, many programming languages were born with the will to propose a first programming experience to beginners, usually through sequences of instructions to execute. However, the programming language FunBlocks explores another approach focusing on state transformations based on term rewriting systems. Additionally, it is an educative programming language providing a visual interface inspired by block programming. The rewriting theory allows the user to create rules consisting in transform string of symbols (called terms) into other ones. Term rewriting has its own theory and contains some properties that are interesting for the learning of computer science. As the majority of these properties are undecidable in general, many verification tools exists, but there are not well suited for an educative purpose.

In an effort to provide an adapted response, we propose the FunBlocks checker that is a verification tool working on FunBlocks. Our tool aims to give the user the possibility to check two important properties, namely termination and confluence, using a simple command line interface. To do this, we use Maude, a language following the rewriting theory and containing a formal environment which can check if no infinite derivation exist (termination) or if each term has at most one normal form (confluence). The goal is to offer an extra educational value to FunBlocks by providing intuitive feedback emphasising on important properties in computer science, though the use of rewrite rules. 
