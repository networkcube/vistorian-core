> **Note**
> The latest code for the Vistorian project is now kept in the [vistorian-monorepo](https://github.com/networkcube/vistorian-monorepo) repository.
> The code for the `vistorian-core` package is [here](https://github.com/networkcube/vistorian-monorepo/tree/master/packages/vistorian-core).


# Vistorian-core

This repository contains the core logic behind networkcube.

Vistorian-core is a dependency for other components but isn't run directly.

The latest stable version can be installed into an npm project with `npm install vistorian-core`.

Alternatively, for development:
* `git clone https://github.com/networkcube/vistorian-core`
* `cd vistorian-core`
* `npm install`


# Code Structure

The core package is divided into a set of modules. It is bundled into a single file `vistorian-core.js`.

* `analytics.ts` provides analytical means for calculating metrics on your network
* `colors.ts` contains some pre-defined color schemes 
* `datamanager.ts` manages the data storage in local storage
* `dynamicgraph.ts` contains the in-memory data structures of the network
* `importers.ts` contains methods for loading data formats into networkcube's `DataSet` objects.
* `main.ts` provides some high-level methods such as creating visualizations and importing data.
* `messenger.ts` contains methods for sending and managing messages between windows
* `motifs.ts` contains methods related to finding and matching graph motifs in the network (w.i.p.)
* `ordering.ts` contains methods and variables to optimze a linear ordering of data elements.
* `queries.ts` contains methods for querying nodes, links, etc.. and their attributes on the network
* `search.ts` provides search functionality
* `utils.ts` provides util methods.
