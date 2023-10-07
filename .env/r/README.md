# R Env using Conda

This environment uses Conda to manage the R installation.

## Create the environment

To build the environment run:

```bash
$ mamba create -n r-environment r-essentials r-base r-languageserver r-httpgd radian
$ mamba activate r-environment
```

<!-- 
## Install packages

```r
install.packages('languageserver')
install.packages('httpgd')
``` -->

## Install vscDebugger

```bash
$ R --no-restore --quiet -f /home/vscode/.vscode-server/extensions/rdebugger.r-debugger-0.5.4/R/install.R --args https://github.com/ManuelHentschel/VSCode-R-Debugger/releases/download/v0.5.4/vscDebugger_0.5.2.tar.gz
```

## Setting path

`r.rterm.linux` and `r.rpath.linux`
