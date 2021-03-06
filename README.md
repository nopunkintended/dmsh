# The Docker-Minideb-Supervisor-Hug (DMSH) stack

In order to provide a working environment for an interconnected tool, and such turning it into an available microservice piece for a more complex structure, a segregated daemon is required. Applying this principle to current technologies provides us with the _API-in-a-Container template_. The **Docker-Minideb-Supervisor-Hug stack** is an application of this template.

## API-in-a-Container
- Container: [docker](https://github.com/docker) - "*platform built for developers to build and run applications*".
- System: [minideb](https://github.com/bitnami/minideb) - "*small image based on Debian by bitnami*".
- Manager: [supervisor](https://github.com/Supervisor/supervisor) - "*process control system for UNIX*".
- API: [hug](https://github.com/timothycrosley/hug) - "*APIs, as simple as possible, but no simpler*".
- *your code here*

## The Container level
Building the microservice inside an isolated and portable environment allows for:
- easier **integration** (isolating constraints and requirements)
- easier **delivery** (regarding distribution and transportability issues)

Note that any internal or intermediate infrastructure (e.g.: development environments, CI/CD toolchains) benefits from the same advantages as the final complex structure.

Aside from [Docker](https://github.com/docker), options for the Container level could go from fully-virtualized machines to segregated environment variables. Docker provides a good compromise between the learning curve and the features versus limitations ratio. Distribution infrastructure already exists through the Docker hub system. Same goes for containers management system, providing an eventual basis for the complex structure.

## The System level
Benefeting from the Container segregation for the microservice System allows for:
- easier **optimisation** (focusing on a smaller set of limitations)
- easier **design** (building upon the minimalist microservice infosystem)

Note that templating easier optimisation and easier design in the same level provides a common playfield between low- and high-level requirements.

Aside from [minideb](https://github.com/bitnami/minideb), options for the System level could go from fully-fledged corporate system to Linux From Scratch. Minideb provides a good compromise between access to open-source software and the user-friendly versus weight ratio. Minideb is shipped with a self-cleaning variant of a package installer in a common server-oriented open-source system, already providing support for both optimisation and design.

## Side-benefits
Including a Container level in the template decouples the underlying structure and the microservice constraints. Providing a more virgin environnment to crafters is a huge plus regarding democratic access to innovation and thus the overall capabilities of complex structures.
