# YANG-Based Modeling and Emulation of Experimental Network Topologies

This artifact accompanies the paper *YANG-Based Modeling and Emulation of Experimental Network Topologies* by Eric Hauser, Johannes Späth, Kento Grüner, and Georg Carle. The artifact consists of three parts.

- [Topology files](topologies/README.md) describe the YANG topology instances for Figures 1 and 2, the research testbed, and the PQ-TLS measurement setup used to reproduce Table 4a.
- [Subtopology search](subtopology-search/README.md) shows how to find the Figure 1 setup in the testbed, first at any link speed and then with a 100 Gbit/s minimum. It includes the Python example and its output.
- [Measurement reproduction on GitHub Pages](https://tumi8.github.io/paper-yang-topologies-demonstration/reproduction) compares the reproduced post-quantum TLS handshake latencies with those reported in Table 4a of Sosnowski et al. The [measurement topology](topologies/table-4a-reproduction.json) describes the client, server, and sniffer.

  The raw reproduction artifact will be available in `docs/reproduction/2026-11-08_16-11-41_109142/` and archived on [Zenodo](https://doi.org/10.5281/zenodo.24062011).

## Disclaimer

The artifact documentation and parts of the subtopology search script (`search.py`) were written with the help of AI coding tools.
