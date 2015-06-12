oXygen Project for DAISY Pipeline 2
===================================

oXygen XML Editor Project for developing modules for the DAISY Pipeline 2 framework.

Features
--------

- XML Catalogs set up to resolve cross-module URIs
- XSLT testing scenario that automatically locates the XSpec file
- XProc testing scenario that automatically locates the xprocspec file
- more to come...


Setup
-----

The directory you check out this repository into, as well as
all the DAISY Pipeline 2 module repositories you want to use,
needs to be checked out in the same directory. For instance:

```sh
mkdir ~/daisy-pipeline
cd ~/daisy-pipeline
git clone https://github.com/josteinaj/oxygen-project.git
git clone https://github.com/daisy/pipeline-modules-common.git
git clone https://github.com/daisy/pipeline-scripts-utils.git
```
This will check out the modules-common and the scripts-utils
repositories, both of which are used in most Pipeline 2 scripts.

The rest of the modules repositories can be checked out in the same way:

```sh
git clone https://github.com/daisy/pipeline-scripts.git
git clone https://github.com/daisy/pipeline-mod-braille.git
git clone https://github.com/daisy/jhyphen.git
git clone https://github.com/daisy/pipeline-mod-audio.git
git clone https://github.com/daisy/pipeline-mod-nlp.git
git clone https://github.com/daisy/pipeline-mod-tts.git
```

You'll also want to check out xprocspec to enable the
projects XProc Testing scenario:

```sh
git clone https://github.com/daisy/xprocspec.git
```

In oXygen, open the DAISY Pipeline 2 project through the
`Project -> Open Project...` menu (or use `CTRL+F2`).
