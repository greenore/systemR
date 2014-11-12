systemR
=======

## Introduction

**systemR** is an open source packages to interact with the operation system (OS) on the shell level.

### Install 

Installing directly from Github requires some helper packages. The easies way to setup **systemR** is to source the following «[init.R][1]» script and then install and run the package with the packagesGithub function. 

#### Windows:
```
source("https://rawgit.com/greenore/initR/master/init.R")
packagesGithub("systemR", repo_name="greenore")
```

#### Linux:
```
source(pipe(paste("wget -O -", "https://rawgit.com/greenore/initR/master/init.R")))
packagesGithub("systemR", repo_name="greenore")
```

[1]: https://github.com/greenore/initR/blob/master/init.R
[2]: http://www.bioconductor.org/packages/release/bioc/html/EBImage.html
