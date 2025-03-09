# Retro-Frame Common Documentation

**Endeavor: Retro-Frame**  
**Repository: \<[http://source.retro-frame.net/common](http://source.retro-frame.net/common)\>**  
**Version: 1.0!1 (dev)**  


## Contents

1. About Retro-Frame

2. Definitions and guidelines

3. Common specifications

4. Document template

5. References


## 1. About Retro-Frame

Retro-Frame is a Retro-Endeavor that provides common documentation (i.e.
definitions, guidelines and templates) as well as specifications which are
intended for use in retrospective programming and may be used as a whole or
partially for other purposes:

* This README file is part of the **Retro-Frame Common Documentation**
  repository which provides common definitions, guidelines, templates and
  specifications. This repository is online available from
  \<[http://source.retro-frame.net/common](http://source.retro-frame.net/common)\>

* Also part of Retro-Frame is the **Retro-Frame Specifications** repository
  which provides individual specifications covering specific topics (i.e.
  algorithms, data formats, protocols and environments). This repository is
  online available from
  \<[http://source.retro-frame.net/spec](http://source.retro-frame.net/spec)\>

As Retro-Frame is evolving, declarations of compliance should always refer to a
specific release version. If a general intention of compliance is expressed, a
reference to the major version may be given by "Retro-Frame 1.x". However, an
actual reference should specify the minor version as well (e.g. "Retro-Frame
1.0").

Note that the individual Retro-Frame specifications (e.g. data formats) may use
independent version numbers.


## 2. Definitions and guidelines

The directory `doc/` contains the following general documents:

* `doc/rf-def.txt` provides common definitions. Additional definitions may be
  part of any documentation.

* `doc/rf-guide.txt` provides guidelines (i.e. normative rules) which must be
  observed for compliance to this version of Retro-Frame. While all Retro-Frame
  guidelines are covered by this single document, other Retro-Endeavors may
  provide subsidiary guidelines.


## 3. Common specifications

The directory `spec/` contains the following common specifications:

* `spec/rf-char.txt` provides a provides a specification of Retro-Frame
  characters, which are a superset of Unicode, and character encodings.

* `spec/rf-path.txt` provides a specification of a universal path
  representation which is used to locate an object on a file system in an
  environment-independent manner. In addition, the translation of a universal
  path from or to a native (i.e. environment-dependent) path is specified.

* `spec/rf-syntax.txt` provides a specification of a metasyntax based on the
  Backus-Naur Form (BNF) and, based on this, specifications of a syntax for
  text respective binary data format specifications. Despite their intended
  use, the metasyntax and/or the syntax specifications may also be used for
  other purposes.

* `spec/rf-types.txt` provides common Retro-Frame codes (i.e. a code list) for
  specified data types. The data types covered are integer, floating point
  number and character types.


## 4. Document template

The directory `template/` contains the generic document template
`template/rf-doc.txt`.

As this template may be used for endeavors other then Retro-Frame, the FIGlet
of the text "\<Retro-Endeavor\>" should be replaced by the name of the actual
endeavor in FIGlet standard font.


## 5. References

### FIGlet

For the official website of FIGlet ("Frank, Ian and Glenn's LETters"), see
\<[http://www.figlet.org/](http://www.figlet.org/)\>.

### Retro-Frame Common Documentation

For the Retro-Frame Common Documentation repository, see
\<[http://source.retro-frame.net/common](http://source.retro-frame.net/common)\>

### Retro-Frame Specifications

For the Retro-Frame Specifications repository, see
\<[http://source.retro-frame.net/spec](http://source.retro-frame.net/spec)\>
