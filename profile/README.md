# TurboPerl

A Turbo Pascal style IDE for Perl.

TurboPerl is a full screen terminal application, written in Free Pascal on
top of Free Vision, the clone of Borland's Turbo Vision that ships with it:
a menu bar across the top, a status line along the bottom, overlapping
windows in between, and the muscle memory of a 1992 Borland IDE pointed at a
modern perl.

**Website: [turboperl.org](https://turboperl.org)**

![TurboPerl editing hello.pl](https://raw.githubusercontent.com/turbo-perl/turboperl/main/docs/hello.png)

## What it does

- Perl syntax highlighting that understands POD, here-documents, the
  quote-like operators and interpolation
- Run a script with Ctrl-F9, or check its syntax with F9
- An integrated debugger: breakpoints, stepping, watches, a call stack and
  evaluate
- perldoc for the word under the cursor
- perltidy and perlcritic, if they are installed

The IDE is in the [turboperl](https://github.com/turbo-perl/turboperl)
repository.
