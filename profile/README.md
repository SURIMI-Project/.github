
# SURIMI Project

**Implementing socio-ecological models into the European Digital Twin Ocean to support marine management and policy development.**

[Project Website](https://www.surimi-project.eu/) | [GitHub Repositories](https://github.com/orgs/SURIMI-Project/repositories) | [Project Wiki](https://github.com/SURIMI-Project/SURIMI-project/wiki)

## About SURIMI

SURIMI is a Horizon Europe research project (2024–2027) developing socio-ecological models to support sustainable fisheries management and marine policy development.

The project brings together ecological, economic, and social models to explore how fisheries, marine ecosystems, and coastal communities respond to different management strategies. These models are integrated into a simulation framework designed to contribute to the [**European Digital Twin Ocean (EU DTO)**](https://www.edito.eu/).

SURIMI also develops graphical user interfaces (GUIs) for exploring marine and fisheries data and configuring, running, and analysing simulations. These include a data GUI and a model GUI, complemented by tools based on large language models (LLMs) that allow users to access, explore, and interpret data and simulation results using natural language.

## Models and Tools

This GitHub organisation hosts the software developed within SURIMI, including individual models, user interfaces, and supporting infrastructure.

### Models

| Model | Description | Repository |
|---|---|---|
| Market model | Simulates first-sale fish prices in local port markets. | [SURIMI-market](https://github.com/SURIMI-Project/SURIMI-market) |
| Product flow value-chain model | Models fish product flows through the value chain. | [SURIMI-value-chain](https://github.com/SURIMI-Project/SURIMI-value-chain) |
| POSEIDON (ABM) | Simulates fishing activities and fleet behaviour. | [SURIMI-poseidon](https://github.com/SURIMI-Project/SURIMI-POSEIDON) |
| MICE ecosystem model | Models interactions between marine species and fisheries. | add link |
| Ecopath with Ecosim (EwE) | Models marine ecosystems and food-web dynamics. | [SURIMI-ecopath](https://github.com/SURIMI-Project/SURIMI-Ecopath) |
| CMSY++ | Supports fish stock assessment. | [SURIMI-CMSY](https://github.com/SURIMI-Project/SURIMI-CMSY) |
| Fisheries Authority (MSE) | Evaluates and implements fisheries management strategies during simulations. | [SURIMI-fisheries-authority](https://github.com/SURIMI-Project/SURIMI-fisheries-authority) |
| NLP assessment model | Provides tools to explore and interpret marine and fisheries data. | [SURIMI-data-mcp](https://github.com/SURIMI-Project/SURIMI-data-mcp) |
| NLP policy model | Provides tools to explore and interpret simulation results. | [SURIMI-model-mcp](https://github.com/SURIMI-Project/SURIMI-model-mcp) |

### User Interfaces

| Tool | Description | Repository |
|---|---|---|
| Data GUI | Graphical user interface for exploring marine and fisheries data. | Private |
| Model GUI | Graphical user interface for configuring, running, and analysing simulations. | Private |
| SURIMI Chat | Natural-language interaction with data and simulation results using LLMs. | Private |

### Infrastructure

| Tool | Description | Repository |
|---|---|---|
| Controller | Coordinates the execution of simulation modules and manages data exchange. | [SURIMI-controller](https://github.com/SURIMI-Project/SURIMI-controller) |
| Output Creator | Processes and prepares simulation outputs. | [SURIMI-output-creator](https://github.com/SURIMI-Project/SURIMI-output-creator) |
| Protocol | Defines communication protocols between simulation modules. | [SURIMI-protocol](https://github.com/SURIMI-Project/SURIMI-protocol) |
| Semantic Registry | Provides semantic information for model interoperability. | [SURIMI-SemanticRegistry-DotNet](https://github.com/SURIMI-Project/SURIMI-SemanticRegistry-DotNet) |
| Data Model | Defines shared data structures used by SURIMI services. | [SURIMI-Datamodel-DotNet](https://github.com/SURIMI-Project/SURIMI-Datamodel-DotNet) |
| Common Library | Provides shared functionality for .NET-based SURIMI modules. | [SURIMI-Common-DotNet](https://github.com/SURIMI-Project/SURIMI-Common-DotNet) |

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

UK participants in SURIMI are funded by UK Research and Innovation (UKRI) under the UK government's Horizon Europe funding Guarantee [grant number 10132993].
