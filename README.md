# Dependencies
Allows to define and handle virtual dependencies.


The functional goals are:
* Create a library which helps to define and handle hierarchally structured dependencies of virtual objects another object may depend on. This may be used to define dependencies as seen in some installers (when automatically selecting other required components), or to define dependencies as required to manage i.e. execution orders.

The non-functional goals are:
* Allow for fast processing in order to enable a high rate of dependency operations, e.g. when handling execution orders of many jobs.
* Executable on Microsoft .NET 4.5, Mono, .NET Core 5.
