*format-all* for Emacs
======================

What does it do
---------------

Lets you auto-format source code in several languages using the exact
same command for all languages, instead of learning a different elisp
package and formatting command for each language.

Just do **M-x** `format-all-the-buffer` and it will try its best to do
the right thing.

For most languages, you will need to install an external program to
help with the formatting.  If you don't have the right program,
`format-all-the-buffer` will try to tell you how to install it.

How to install
--------------

From [MELPA](https://melpa.org/#/?q=format-all])

Supported languages
-------------------

* C/C++ (clang-format)
* D (dfmt)
* Elm (elm-format)
* Emacs Lisp (native)
* Go (gofmt)
* Haskell (hindent)
* Js (standard)
* Python (autopep8)
* Ruby (rufo)
* Shell script (shfmt)

Adding new languages
--------------------

New formatters can be added easily if they are external programs that
can read code from stdin and format it to stdout.

How to report bugs
------------------

GitHub issues are preferred. Email is also ok. Feature requests are
welcome. PRs are very welcome, but for non-trivial changes please open
an issue to coordinate with me first.