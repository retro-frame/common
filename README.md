# Retro-Frame Common Documentation

**Endeavor: Retro-Frame**  
**Repository: \<[http://source.retro-frame.net/common](http://source.retro-frame.net/common)\>**  
**Version: 1.0.1**  
**Compliance: Retro-Frame 1.0**  
**License: MIT (see `LICENSE`)**  

Copyright (c) 2025-2026 Ingo Boehmer \<ingo@retro-leisure.net\>

All product names, logos, and brands are property of their respective owners.


## Contents

1. Overview

2. General common documentation

3. Common specifications

4. Templates

5. References


## 1. Overview

**Retro-Frame** is a Retro-Endeavor that provides common documentation (i.e.
definitions, guidelines, templates and generic specifications, covered by this
repository) as well as topic-related specifications (covered by individual
repositories) which are intended for use in retrospective programming and may
be used as a whole or partially for other purposes.

* This README file is part of the ***Retro-Frame Common Documentation***
  repository which provides common definitions, guidelines, templates and
  generic specifications.

* Also part of Retro-Frame are individual ***Retro-Frame Specifications***
  repositories which provide specifications covering specific topics (e.g. data
  formats, codepages, algorithms or protocols). These repositories may be
  online available from the **Retro-Frame** homepage.

As Retro-Frame is evolving, declarations of compliance should always refer to a
specific release version of the Retro-Frame Common Documentation respository.
If a general intention of compliance is expressed, a reference to the major
version may be given by "Retro-Frame 1.x". However, an actual reference should
specify the minor version as well (e.g. "Retro-Frame 1.0").

Note that the individual topic-related specifications (e.g. a data format)
use independent version numbers and the repositories may have different minor
versions than the Retro-Frame Common Documentation respository.


## 2. General common documentation

The directory `doc/` contains the following general common documentation:

* `doc/rf-def.txt` provides common definitions. Additional definitions may be
  part of any documentation.

* `doc/rf-guide.txt` provides guidelines (i.e. normative rules) which should be
  observed for compliance to this version of Retro-Frame. While all Retro-Frame
  guidelines are covered by this single document, other Retro-Endeavors may
  provide subsidiary guidelines.


## 3. Common specifications

The directory `spec/` contains the following common specifications:

* `spec/rf-char.txt` provides a specification of Retro-Frame characters, which
  are a superset of Unicode, and corresponding character encodings.

* `spec/rf-path.txt` provides a specification of a universal path
  representation which is used to locate an object on a file system in an
  environment-independent manner. In addition, the translation of a universal
  path from or to a native (i.e. environment-dependent) path is specified.

* `spec/rf-syntax.txt` provides a specification of a metasyntax and, based on
  this, specifications of a syntax for text respective binary data format
  specifications. Despite their intended use, the metasyntax and/or the syntax
  specifications may also be used for other purposes.

* `spec/rf-types.txt` provides common Retro-Frame codes (i.e. a code list) for
  specified data types. The data types covered are integer, floating point
  number and character types.


## 4. Templates

The directory `template/` contains the following templates:

* `template/rf-readme.md` provides a generic readme file template in
  **Markdown** format.

* `template/rf-doc.txt` contains the generic document template in text format.
  As this template may be used for endeavors other than Retro-Frame, the
  **FIGlet** of the text "\<Retro-Endeavor\>" should be replaced by the name of
  the actual endeavor in **FIGlet** standard font.


## 5. References

### FIGlet

Official website of FIGlet ("Frank, Ian and Glenn's LETters"), see
\<[http://www.figlet.org/](http://www.figlet.org/)\>.

### Markdown

Markdown homepage by John Gruber, Daring Fireball Company LLC., see
\<[https://daringfireball.net/projects/markdown/](https://daringfireball.net/projects/markdown/)\>.

### Retro-Frame

Retro-Frame homepage, see
\<[http://source.retro-frame.net/](http://source.retro-frame.net/)\>.
