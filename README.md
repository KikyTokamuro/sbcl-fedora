# SBCL package for Fedora

[![Copr build status](https://copr.fedorainfracloud.org/coprs/kiky-tokamuro/sbcl/package/sbcl/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/kiky-tokamuro/sbcl/package/sbcl/)

[Steel Bank Common Lisp (SBCL)](https://www.sbcl.org/) is a high performance Common Lisp compiler. It is open source / free software, with a permissive license. In addition to the compiler and runtime system for ANSI Common Lisp, it provides an interactive environment including a debugger, a statistical profiler, a code coverage tool, and many other extensions.

This repository is used to generate the Copr repo [kiky-tokamuro/sbcl](https://copr.fedorainfracloud.org/coprs/kiky-tokamuro/sbcl/).

To install, first enable the repository
```
dnf copr enable kiky-tokamuro/sbcl
```

and then install the package itself by running
```
sudo dnf install sbcl
```