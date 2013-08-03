# async-plgd

### hoare:

Examples corresponding to those in C.A.R. Hoare,
"Communicating Sequential Processes" (CACM 21:8 August 1978).
This paper is the precursor to his book of the same title,
which can be obtained at http://www.usingcsp.com/

#### coroutines.clj:

section 3 of the paper, "Coroutines"

#### subroutines.clj:

section 4 of the paper, "Subroutines"

#### monitors.clj:

section 5 of the paper, "Monitors and Scheduling"

#### misc.clj:

section 6 of the paper, "Miscellaneous"

## Usage

Clone the [core.async](http://github.com/clojure/core.async) repo to a
convenient location. `cd` into the repo and run `lein install`.

Then clone this repo into a convenient location and `cd` into it.

Then open a repl, and at the prompt, type

```
(use 'hoare.coroutines)
```
or

```
(use 'hoare.subroutines)
```
or

```
(use 'hoare.monitors)
```
or

```
(use 'hoare.misc)
```

and run any of the test functions in the corresponding .clj file.

But mainly, read the source. Comments, corrections, criticisms are welcome.

## License

Copyright © 2013 Alan Shaw

Distributed under the Eclipse Public License, the same as Clojure.
