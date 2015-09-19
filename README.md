# Dependencies
Allows to define and handle virtual dependencies.


The functional goal is to create a library which helps to define and handle hierarchally structured dependencies of virtual objects another object may depend on. This may be used to define dependencies as seen in some installers (when automatically selecting other required components), or to define dependencies as required to manage i.e. execution orders.

The non-functional goal is to allow for fast processing in order to enable high throughput with many dependency checks, e.g. when handling execution orders of many jobs.
