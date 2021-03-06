# DiPOSH documentation

DiPOSH is an evolution from POSH: Paris OpenSHMEM. POSH was designed to run on a single node over shared memory, DiPOSH is a distributed version; hence Distributed POSH.

DiPOSH is written in C++, trying to take advantage of an object-oriented architecture for composability and of templates. 

Some design and implementation documents:
* [Communication drivers](communication_drivers.md)
* [Collective communications](collective_communications.md)
* [Launcher and run-time environment](rte.md)
* [Fault tolerance](ft_cl.md)