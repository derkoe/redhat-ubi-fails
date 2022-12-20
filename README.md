# Red Hat UBI Issues

This shows some of the stuff that Red Hat UBI images just get wrong:
1. Module handling (dnf module) is quite strange and not consistent
2. UBI only includes a subset of packages which leads to errros when installing software

Look at the [`Makefile`](Makefile) and run the goals.
