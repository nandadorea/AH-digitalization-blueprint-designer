# Architecture Decision Log

## ADR-0001

Title

The Design System focuses on animal health surveillance.

Status

Accepted

Reason

Version 1 should provide deep guidance within a clearly defined scope.

Future versions may extend the methodology to other domains.

---

## ADR-0002

Title

The Design System is AI-native.

Status

Accepted

Reason

The methodology shall be sufficiently structured to support both human users and AI agents without requiring separate interpretations.

---

## ADR-0003

Title

Capabilities are described independently of software.

Status

Accepted

Reason

Countries should be able to implement the methodology using technologies appropriate to their own context.

--

## ADR-0004

Title

A Digitalization Blueprint describes exactly one capability.

Status

Accepted.

Decision

Each Digitalization Blueprint shall describe exactly one surveillance capability.

Multiple related capabilities shall be documented as separate Blueprints and may later be combined within a Digitalization Roadmap or implementation programme.

Rationale

Keeps each Blueprint focused and easy to understand.
Encourages reuse across countries and implementation projects.
Simplifies review and maintenance.
Supports AI-assisted generation and validation.
Allows capabilities to evolve independently.

--

##ADR-0005

Title

Normative requirements shall have persistent identifiers.

Status

Accepted.

Decision

All normative requirements defined by the Design System shall receive stable identifiers.

Identifiers shall remain unchanged across versions unless the requirement is removed.

Rationale

Persistent identifiers allow:

unambiguous referencing
AI validation
reviewer checklists
cross-references between documents
future traceability

--

##ADR-0006

Title

The Design System shall not prescribe the Blueprint catalogue.

Decision

The Design System defines the structure of a Digitalization Blueprint but does not prescribe which surveillance capabilities require one.

The collection of available Blueprints evolves independently within the Guidelines repository.

This cleanly separates framework from content.

--

## ADR-0007 

Title
The Design System adopts ISO normative language conventions.

Specifically:

Word	Meaning
shall	Mandatory requirement
should	Strong recommendation
may	Optional
must not	Prohibition


Consequences

Large implementation programmes will consist of multiple Blueprints.
Relationships between capabilities are documented through references rather than by expanding Blueprint scope.

--


