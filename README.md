
***

![/Erlang_logo.svg](/Erlang_logo.svg)

### Learning Erlang (programming language)

I know very little about the Erlang programming language. This document will go over all of my knowledge of the Erlang programming language.

#### Hello World in Erlang

This is how you make a normal Hello World program in Erlang:

```erlang
-module(hello_world).
-compile(export_all).
hello() ->
    io:format("hello world~n").
```

_/!\ This example has not been tested yet, and may not work_

#### Comments in Erlang

Comments in Erlang are the same as in languages like PostScript.

##### Single line comments

Single line comments in Erlang are written like so:

```erlang
%% This is a single line comment
```

##### Multi-line comments

Erlang does not support multi-line comments.

#### Break keyword in Erlang

Erlang does not support the `break` keyword.

<!--
To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_
!-->

#### Factorials in Erlang

A factorial can be defined like so:

```erlang
fac(0) -> 1;
%% if 0, return 1, semicolon means `else`
```

_/!\ This example has not been tested yet, and may not work_

#### Fibonacci sequence in Erlang

Here is an undocumented Fibonacci sequence program written in Erlang.

```erlang
-module(series).
-export([fib/1]).

fib(0) -> 0;
fib(N) when N < 0 -> err_neg_val;
fib(N) when N < 3 -> 1;
fib(N) -> fib_int(N, 0, 1).

fib_int(1, _, B) -> B;
fib_int(N, A, B) -> fib_int(N-1, B, A+B).
```

_/!\ This example has not been tested yet, and may not work_

#### Modules in Erlang

Erlang programs are defined with the `-module` line at the beginning. This can be written like so:

```erlang
-module(myModule)
-export(0)

myModule1():
    io:format("Erlang module").
```

_/!\ This example has not been tested yet, and may not work_

#### Other knowledge of the Erlang programming language

1. Erlang is a language by Joe Armstrong, Robert Virding, and Mike Williams

2. Erlang is not a semicolon and curly bracket language, but it is a semicolon language

3. Erlang uses the `*.erl` file extension by default.

4. Erlang also uses the `*.hrl` file extension

5. Erlang originally was a proprietary language, but was later made open source

6. Erlang is used in the development of WhatsApp

7. Erlang was created in 1986 

8. Erlang is not one of the top 50 programming languages (as of 2022, July 31st, it has never ranked 50 or higher on the TIOBE index, but it has ranked in the top 100) source: [TIOBE index](https://www.tiobe.com/tiobe-index/)

9. Erlang is a language recognized by GitHub (as of 2022, Tuesday, August 2nd)

10. Erlang is a "let it crash" styled langaueg

11. No other knowledge of the Erlang programming language

#### Additional comments

1. I have not yet memorized the names of the developers

2. No other additional comments available

***

## File info

**File type:** `Markdown document (*.md *.mkd *.mdown *.markdown)`

**File version:** `1 (2022, Tuesday, August 2nd at 4:23 pm PST)`

**Line count (including blank lines and compiler line):** `180`

***

## File history

<details><summary><p>Click/tap here to expand/collapse the history for this file</p></summary>

<details><summary><p><b>Version 1 (2022, Tuesday, August 2nd at 4:23 pm PST)</b></p></summary>

> Changes:

> * Started the file

> * Added the `title` section

> * Added the `Hello World in Erlang` section

> * Added the `Object Oriented Hello World in Erlang` section

> * Added the `Comments in Erlang` section

> > * Added the `Single line comments` subsection

> > * Added the `Multi-line comments` subsection

> * Added the `break keyword in Erlang` section

> * Added the `Factorials in Erlang` section

> * Added the `Fibonacci sequence in Erlang` section

> * Added the `Modules in Erlang` section

> * Added the `other knowledge of the Erlang programming language` section

> * Added the `Additional comments` section

> * Added the `file info` section

> * Added the `file history` section

> * No other changes in version 1

</details>

</details>

***
