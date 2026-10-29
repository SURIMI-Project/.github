
# SURIMI Project

**Implementing socio-ecological models into the European Digital Twin Ocean to support marine management and policy development.**

[Project Website](https://www.surimi-project.eu/) | [GitHub Repositories](https://github.com/orgs/SURIMI-Project/repositories) | [Project Wiki](https://github.com/SURIMI-Project/SURIMI-project/wiki)

## About SURIMI

SURIMI is a Horizon Europe research project (2024–2027) developing socio-ecological models to support sustainable fisheries management and marine policy development.

The project brings together ecological, economic, and social models to explore how fisheries, marine ecosystems, and coastal communities respond to different management strategies. These models are integrated into a simulation framework designed to contribute to the **European Digital Twin Ocean (EU DTO)**.

SURIMI also develops graphical user interfaces (GUIs) for exploring marine and fisheries data and configuring, running, and analysing simulations. These include a data GUI and a model GUI, complemented by tools based on large language models (LLMs) that allow users to access, explore, and interpret data and simulation results using natural language.

## Software and Models

This GitHub organisation hosts the software developed within SURIMI, including individual models, simulation services, and supporting tools.

### Socio-ecological Models

| Model | Description | Repository |
|---|---|---|
| System dynamics economic model | Simulates first-sale fish prices in local port markets. | [SURIMI-market](https://github.com/SURIMI-Project/SURIMI-market) |
| Product flow value-chain model | Models fish product flows through the value chain. | [SURIMI-value-chain](https://github.com/SURIMI-Project/SURIMI-value-chain) |
| Agent-based model (POSEIDON) | Simulates fishing activities and fleet behaviour. | [SURIMI-POSEIDON](https://github.com/SURIMI-Project/SURIMI-POSEIDON) |
| Ecopath with Ecosim (EwE) | Models marine ecosystems and food-web dynamics. | [SURIMI-Ecopath](https://github.com/SURIMI-Project/SURIMI-Ecopath) |
| CMSY++ | Supports fish stock assessment. | [SURIMI-CMSY](https://github.com/SURIMI-Project/SURIMI-CMSY) |
| NLP data model | Provides tools to explore and interpret marine and fisheries data. | [SURIMI-data-mcp](https://github.com/SURIMI-Project/SURIMI-data-mcp) |
| NLP policy model | Provides tools to explore and interpret simulation results. | [SURIMI-model-mcp](https://github.com/SURIMI-Project/SURIMI-model-mcp) |

### Simulation Framework

SURIMI uses a modular simulation framework to connect models and exchange data during simulation runs.

Key repositories include:

- [SURIMI-controller](https://github.com/SURIMI-Project/SURIMI-controller) – Coordinates the execution of simulation modules.
- [SURIMI-protocol](https://github.com/SURIMI-Project/SURIMI-protocol) – Defines communication protocols between modules.
- [SURIMI-fisheries-authority](https://github.com/SURIMI-Project/SURIMI-fisheries-authority) – Implements fisheries management decisions within simulations.

Additional repositories and tools are available in the [SURIMI GitHub organisation](https://github.com/orgs/SURIMI-Project/repositories).

## Documentation

Documentation, installation instructions, and usage examples are maintained in the individual repositories.

The [SURIMI project repository](https://github.com/SURIMI-Project/SURIMI-project) provides access to project-wide issues and the [project Wiki](https://github.com/SURIMI-Project/SURIMI-project/wiki).

For information about the research project, partners, and results, visit the [official SURIMI website](https://www.surimi-project.eu/).

## Funding

<p>
  <img src="https://raw.githubusercontent.com/SURIMI-Project/SURIMI-POSEIDON/main/.github/images/funded_by_the_eu.svg#gh-light-mode-only" alt="Funded by the European Union" height="60">
  <img src="https://raw.githubusercontent.com/SURIMI-Project/SURIMI-POSEIDON/main/.github/images/funded_by_the_eu_dark.svg#gh-dark-mode-only" alt="Funded by the European Union" height="60">
  &nbsp;
  <img src="https://raw.githubusercontent.com/SURIMI-Project/SURIMI-POSEIDON/main/.github/images/ukri_logo.png#gh-light-mode-only" alt="UK Research and Innovation" height="60">
  <img src="https://raw.githubusercontent.com/SURIMI-Project/SURIMI-POSEIDON/main/.github/images/ukri_logo_dark.png#gh-dark-mode-only" alt="UK Research and Innovation" height="60">
</p>

Funded by the European Union under the Horizon Europe Program, Grant Agreement No. 101157456 (SURIMI). Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Climate, Infrastructure and Environment Executive Agency (CINEA). Neither the European Union nor the granting authority can be held responsible for them.

UK participants in SURIMI are funded by UK Research and Innovation (UKRI) under the UK government’s Horizon Europe funding Guarantee [grant number 10132993].
