# Mandelbrot - a simple language benchmark

Run a computation of the Mandelbrot set in various languages. The variants are designed to be more or less equivalent, printing the output only at the end to reduce the dependency of I/O to a minimum. Thus, only FP comuputation is measured.

To try a language, do the following steps:

1. Checkout this repository

2. Run \<language>/prepare.sh

3. Run \<language>/run.sh

Naturally, you need to install a compiler and runtime environment for each language you want to use. The `prepare` script calls the compiler with the required parameters, the `run` script executes the program in the desired language and prints out the elapsed time.