## Hi there 👋

I use this organiztion to section off my demos for my [website](https://jareddyreson.xyz) and uses Docker to help separate resources.

A base Ubuntu 21.04 server release is used as the primary operating system to host these instances.
At `/var/lib/webapplications` we store all the Git repositories and can pull incrementally for changes made offsite.
The structure of this directory is as follows:
- Algorithms
  - RPN Calculator
  - Cella Ant 0x15
  - Sorting Olympics
  - Balloon Juice
- Database
  - University Manager
- Documentation
  - Python Documentation
- React
  - Expresso
  - Grok 19

The goal was not make this server a development environment, rather a showcase that can be easily replicated.
A [script](https://github.com) has been developed to help automate this process.
The ports will start from 5000 and go from there.
The following port map can be seen here:

- 5000: personal website
- 5001: sorting-olypmics
- ETC
