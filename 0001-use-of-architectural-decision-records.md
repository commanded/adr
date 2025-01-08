# 1. Use of Architectural Decision Records

Date: 2025-01-08

## Status

accepted

## Context

What is the issue that we're seeing that is motivating this decision or change?

People often have ideas about how the libraries in the Commanded ecosystem
could be updated to meet specific needs. Up until now, these ideas have been
hashed out in a combination of Slack channel discussions and GitHub
discussions/issues/PRs on individual repositories. This makes it difficult to
keep track of what things are just in the initial ideation phase vs. what is
being proposed as an actual solution to a problem.

## Decision

What is the change that we're proposing and/or doing?

Any changes to the libraries in the commanded ecosystem (that is, the
repositories under the <https://github.com/commanded> organization) should be
proposed in the form of an ADR in this repository
(<https://github.com/commanded/adr>). Unlike PRs on individual repositories,
there is not necessarily an expectation that ADRs are associated with completed
code changes; rather an accepted ADR provides guidance on *how* to make
changes, what types of dependencies and external technologies we will support,
how the project will be governed, etc. going forward.

## Consequences

What becomes easier or more difficult to do because of this change?

This change will make it easier for the Commanded maintainers to keep track of
serious proposals for changes to the Commanded ecosystem and will help ensure
that such changes are visible to the broader community for consideration and
comment before a final decision is made. Furthermore, it will help us link
together changes that span multiple libraries in different repositories by
providing a central place to reference the code and PRs involved in making the
change.
