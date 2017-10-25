# quil-syntax-highlighter
### Quil (Quantum Instruction Language) syntax highlighter ###

Provides a file template and syntax highlighting in PyCharm (by JetBrains) for the Quil quantum instruction language, which is introduced in the following paper:

Smith, Curtis, and Zeng (2016, August 11). A Practical Quantum Instruction Set Architecture	[arXiv:1608.03355](https://arxiv.org/abs/1608.03355) [quant-ph].

#### Implementation instructions ####
1. Download the file named **file-templates-types-schemes.jar** 
2. Import the file into PyCharm using the **File | Import Settings...** dialog.

The Quil file type (extension **quil**) should appear in **New** file dialogs. Quil keywords including directives, instructions, and gates, should be highlighted. Here is a simple example when the PyCharm default color scheme is selected:

![Syntax highlighting example](https://github.com/JavaFXpert/quil-syntax-highlighter/blob/master/default-scheme-example.png)

#### Known issues ####
Hyphenated keywords are only highlighted up to their hyphens.  
