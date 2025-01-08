# Architectural Decision Records for the Commanded Ecosystem

An architecture decision record (ADR) is a document that captures an important
architectural decision made along with its context and consequences.

The ADRs in this repository are used to document the architectural decisions
for the Commanded Ecosystem, which includes the following repositories:

* [adr](https://github.com/commanded/adr)
  * This repository and the ADR system itself.
* [commanded](https://github.com/commanded/commanded)
  * Use Commanded to build Elixir CQRS/ES applications
* [eventstore](https://github.com/commanded/eventstore)
  * Event store using PostgreSQL for persistence
* [commanded-eventstore-adapter](https://github.com/commanded/commanded-eventstore-adapter)
  * EventStore adapter for Commanded
* [commanded_audit_middleware](https://github.com/commanded/commanded_audit_middleware)
  * Command auditing middleware for Commanded CQRS/ES applications
* [commanded_ecto_projections](https://github.com/commanded/commanded_ecto_projections)
  * Read model projections for Commanded using Ecto
* [eventstore-dashboard](https://github.com/commanded/eventstore-dashboard)
  * Real-time dashboard for EventStore
* [generator](https://github.com/commanded/generator)
  * Commanded application generator
* [commanded-extreme-adapter](https://github.com/commanded/commanded-extreme-adapter)
  * EventStore adapter for Commanded using the Extreme library
* [commanded-scheduler](https://github.com/commanded/commanded-scheduler)
  * Schedule one-off and recurring commands for Commanded CQRS/ES applications
* [commanded-swarm-registry](https://github.com/commanded/commanded-swarm-registry)
  * Distributed process registry using Swarm for Commanded

## ADR Tooling

We recommend using the [adrgen](https://github.com/asiermarques/adrgen) tool to
manage ADR files. However, any tool can be used so long as the resulting ADR
documents use the same [template](./adr_template.md) and the correct status and
ADR number is applied.

## ADR process

1. Before creating an ADR you should first [create a
  discussion](https://github.com/commanded/adr/discussions/new?category=ideas)
  to explore the problem-space with both the maintainers and other community
  members. By engaging in some informal discussion before-hand, you can better
  gauge whether your idea is likely to be adopted in the long run and potentially
  save yourself from a great deal of wasted effort.

2. Once you are ready to create your ADR, simply clone this repository and use
   the aforementioned ADR tooling to create your ADR.

3. When you are ready to get feedback on your ADR, submit a Pull Request to
   this repository.

4. When a decision is reached by the Commanded maintainers, your ADR will be
   merged into the main branch with the appropriate ADR status, so that we have
   a record of all decisions related to the evolution of the Commanded ecosystem.
