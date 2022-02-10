# Benchmarks and Experiments for PLDI 2022 Submission 672

Our experiments are split across two suites: suite \#1 contains 50 theorems that require lemma synthesis distilled from the VCDryad benchmarks, and suite \#2 contains \~650 synthetically generated theorems and lemmas.

This directory contains the following data files:
- *vcdryad_suite.txt:* contains the theorem along with the recursive definitions appearing in it for each benchmark in suite \#1.
- *vcdryad_suite.log:* contains the output of our tool on each benchmark in suite \#1, particularly the valid lemmas discovered while solving each benchmark. We solve all 50 theorems in this suite.
- *synth_suite.txt:* contains the theorem for each benchmark in suite \#2. It also contains the recursive definition of 'tree', a datastructure over two pointers about which the theorems are stated. The specific definition of tree is different in each benchmark and is generated procedurally by varying several parameters as described in Section 4.3.
- *synth\_suite_success.log:* contains the list of valid lemmas discovered by our tool for each benchmark in suite \#2 where our tool was successful (578 benchmarks).
