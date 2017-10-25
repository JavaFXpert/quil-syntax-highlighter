# quil-syntax-highlighter
### Quil (Quantum Instruction Language) syntax highlighting ###

Provides a file template and syntax highlighting in PyCharm (by JetBrains) for the Quil quantum instruction language, which is introduced in the following paper:

Smith, Curtis, and Zeng (2016, August 11). A Practical Quantum Instruction Set Architecture	[arXiv:1608.03355](https://arxiv.org/abs/1608.03355 target="_blank") [quant-ph].

#### Implementation instructions ####
1. Download the file named **file-templates-types-schemes.jar** 
2. Import the file into PyCharm using the **File | Import Settings...** dialog.

The Quil file type (extension **quil**) should appear in **New** file dialogs. Quil keywords including directives, instructions, and gates, should be highlighted.

#### Known issues ####
Hyphenated keywords are only highlighted up to their hyphens.  
