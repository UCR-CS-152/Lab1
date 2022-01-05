CS152 Lab: A Calculator Example
===================================

[home page for lab1](https://www.cs.ucr.edu/~dtan004/proj1/lab01_lexer.html)

[home page for lab2](https://www.cs.ucr.edu/~dtan004/proj2/lab02_parser.html)


## Tools preparation

Make sure you have a Linux environment for this project. You can use 'bolt', your own Linux machine, or Windows Subsystem for Linux(WSL). I highly recommend you directly use 'bolt' since it contains all the necessary tools preinstalled. 

```sh
ssh <your-net-id>@bolt.cs.ucr.edu
```

Make sure you have the following tools installed and check the version:
1. flex -V       (>=2.5)
2. git --version (>=1.8)
3. make -v       (>=3.8)
4. gcc -v        (>=4.8)
5. g++ -v        (>=4.8 optional if you wish to use C++)

## Clone 

Use 'git' to clone the project template:

```sh
    git clone <your-repo-link> lab1
```

## Check Your Tasks for Lab 1

Read the documentation of flex and your tasks in [home page for lab1](https://www.cs.ucr.edu/~dtan004/proj1/lab01_lexer.html). From this starter template, you can edit 'calc.lex' to finish tasks step by step.  


## Keep your progress by uploading to Github

After you finish all 4 tasks, you are done today. You don't need to submit the code but should keep your progress for next time when we start syntax analysis. 

Uploading to Github is a safe way:

```sh
git add .
git commit -m "lab1 - lexer"
git push
```

