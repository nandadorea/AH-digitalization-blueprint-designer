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

## ADR-0008

Title

Normative concepts shall be defined exactly once.

Decision

Each normative concept shall have a single authoritative definition contained within the Blueprint Canon.

Other documents may reference, but shall not redefine, those concepts.

Rationale

Single-source definitions:

reduce ambiguity;
improve maintainability;
simplify AI interpretation;
prevent conflicting terminology.

--

## ADR-0009

Title

Blueprints are composed of Components.

Decision

A Digitalization Blueprint is composed of Blueprint Components rather than directly of Building Blocks.

Building Blocks are one Component type within the Blueprint Architecture.

Rationale

Separating Components from Concepts creates a stable metamodel and allows future extension without changing the Design System.

--

## ADR-0010

Title

The Design System separates Semantics, Structure and Presentation.

Decision

The Design System is organized into three complementary layers:

Semantic Layer
Structural Layer
Presentation Layer

Each layer shall evolve independently while maintaining compatibility with the others.

--

## ADR-0011

Title

Building Blocks remain semantic concepts.

Decision

The Blueprint Canon defines Building Blocks as concepts.

The Blueprint Architecture defines Building Block Components.

These are distinct but related constructs.

--

## ADR-0012

Title

The Design System distinguishes Concepts, Components and Presentation.

Decision

Each reusable element is represented in three complementary forms:

Concept (semantic definition)
Component (structural definition)
Presentation (visual representation)

These representations shall remain independent while describing the same underlying element.
