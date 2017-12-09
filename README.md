# C++14 Standard Reading Notes

## Purpose

C++14 Standard Reading Notes.

C++14 国际标准 与 阅读笔记.



## Background

> "In `GCC 6`, the default mode for C++ is now `-std=gnu++14` instead of `-std=gnu++98`."
>
> See [here](https://gcc.gnu.org/gcc-6/changes.html).



The ISO C++14 standard is officially known as **ISO/IEC 14882:2014**. See [here](https://www.iso.org/standard/64029.html).

C++14 is intended to be a small extension over C++11, featuring mainly bug fixes and small improvements.



C++ standards drafts are at [cplusplus/draft](https://github.com/cplusplus/draft). The closest available draft for C++14 is n4140.

- n3337 = C++11 + editorial fixes.
- n4140 = C++14 + editorial fixes.




## Instructions

Install packages on Debian-based systems, or equivalent things on other systems:

> `sudo apt-get install texlive-full latexmk`



To typeset the draft document, from the `source` directory:

>  run `latexmk -pdf std`

That's it!

You should now have an `std.pdf` containing the typeset draft.


