# MOFBuilder Library

A community-driven repository for expanding the **node library and customizable topology database** used in **MOFBuilder**, enabling researchers to contribute coordination nodes, linkers, and topology definitions for automated metal–organic framework (MOF) construction.

---

## Overview

MOFBuilder constructs metal–organic frameworks by assembling predefined building units (nodes and linkers) according to topology templates.  
The diversity and chemical accuracy of generated MOF structures therefore depend on the quality and coverage of the underlying building block libraries.

This repository provides a **community-maintained dataset of MOF building units**, including:

- Coordination **nodes**
- **Topology templates**
- **Coordination fragments**
- Associated **metadata**

By welcoming contributions from the community, this project aims to continuously expand the accessible chemical space of MOFs for **computational screening, structure generation, and materials discovery**.

---

## Current Status

The node library is currently under active development.

Currently supported features include:

- Carboxylate-type coordinating groups (`-COO⁻`, ABB-type)
- Node fragments extracted from experimental structures
- Support for chain-type nodes

Nodes can be generated from experimental **CIF structures** by marking coordination atoms and cutting clusters according to the MOFBuilder node definition rules.

---

---

## Contributing

We welcome contributions from all **MOFBuilder users**.

You can contribute by:

- Adding new **coordination nodes**
- Uploading **topology templates**
- Providing **example structures**
- Improving **metadata and annotations**
- Reporting issues or suggesting improvements

### Adding a Node

Nodes can be generated from **experimental CIF files** by:

1. Identifying the coordination environment of the metal cluster
2. Marking atoms belonging to the coordinating groups
3. Cutting the cluster following the MOFBuilder node definition rules
4. Uploading the processed node structure to the `nodes/` directory

More detailed instructions will be provided in the `docs/` folder.

---

## Goal

The goal of this repository is to build a **comprehensive and reusable dataset of MOF building blocks** that enables:

- Automated MOF construction
- Large-scale MOF generation
- Data-driven MOF discovery
- Machine learning applications in porous materials

---

## Related Project

This repository supports the **MOFBuilder** framework generation tool.
