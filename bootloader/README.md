# Bootloader test cases

This folder contains programs and PIEs (Position Independent Executables) to run on top of the Starknet bootloader.
The programs are not compiled in proof mode as they are run by the bootloader which is itself compiled in proof mode.

## Programs

* `fibonacci` is a simple Fibonacci program that does not use any builtin or hint.

## PIEs

* `fibonacci` is a simple Fibonacci program that does not use any builtin or hint (same as the `fibonacci` program, as a PIE).
* `fibonacci-stone-e2e` is an alternative Fibonacci program that uses a hint to 