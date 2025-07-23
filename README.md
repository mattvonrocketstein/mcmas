# MCMAS

A mirror of the [MCMAS project](https://sail.doc.ic.ac.uk/software/mcmas/).

MCMAS is a model checker for multi-agent systems that supports temporal epistemic logic.  MAS descriptions are given by means of programs written in the ISPL language.  ISPL is an agent-based, modular language inspired by interpreted systems, a popular semantics.  It describes things like: agents, groups, environments, states, evolutions, protocols, and fairness.  Temporal logic operators include AG/EF/AX. Epistemic logic supports K/GK/GCK/DK.  See the [docs folder](docs/) for manuals, [original README](README) for credits.

Currently pinned to v1.3.0, which **does not compile** for recent versions of linux without downgrading bison.  See [docker-mcmas.git](https://github.com/mattvonrocketstein/docker-mcmas) repository for a docker container.  See [py-mcmas.git](https://github.com/mattvonrocketstein/py-mcmas) repository for a (experimental, work-in-progress) wrapper.