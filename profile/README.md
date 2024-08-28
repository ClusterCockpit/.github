ClusterCockpit is a set of components to build a job-specific and cluster-wide monitoring solution in HPC data centers. It consists of the following components:
* [cc-backend](https://github.com/ClusterCockpit/cc-backend):  A REST and GraphQL API backend. Also provides web ui. This is the core component of ClusterCockpit.
* [cc-metric-collector](https://github.com/ClusterCockpit/cc-metric-collector): A node agent to collect and forward metrics.
* [cc-metric-store](https://github.com/ClusterCockpit/cc-metric-store): A metric timeseries in-memory cache.

ClusterCockpit follows [standardized specifications](https://github.com/ClusterCockpit/cc-specifications) for data formats and interfaces.
For more information visit the [ClusterCockpit website](https://clustercockpit.org).

**Funding** ClusterCockpit is funded within the BMBF GreenHPC EE-HPC project.
