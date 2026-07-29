# Contributing to the AH Digitalization Blueprint Designer

Thank you for contributing to the AH Digitalization Blueprint Designer.

This repository contains the Design System used to develop Digitalization Blueprints for animal health surveillance. The objective is not simply to document workflows, but to provide a reusable methodology that promotes consistency, interoperability and long-term maintainability.

Every contribution should strengthen the Design System rather than solve a single problem.

---

# Guiding Philosophy

Contributors should aim to:

- improve clarity;
- reduce ambiguity;
- maximise reuse;
- preserve technology independence;
- support interoperability;
- maintain consistency across all Blueprints.

When in doubt, prefer extending the methodology over creating exceptions.

---

# Before Contributing

Before proposing a change, ask the following questions:

1. Does this improve the Design System rather than a single Blueprint?

2. Can an existing concept be reused instead of introducing a new one?

3. Is this independent of any specific software platform?

4. Will this remain useful as technologies evolve?

5. Would this change improve both human understanding and AI interpretation?

If the answer to any of these questions is "No", reconsider whether the proposed change belongs in the Design System.

---

# Normative vs Informative Content

This repository distinguishes between two types of content.

## Normative

Normative content defines the Design System.

Examples include:

- definitions;
- design principles;
- mandatory requirements;
- visual language;
- authoring rules.

Normative content establishes the standard.

---

## Informative

Informative content explains how to apply the standard.

Examples include:

- templates;
- examples;
- reference Blueprints;
- implementation guidance.

Informative content illustrates the standard but does not define it.

---

# Architecture Decisions

Major changes to the Design System should be documented as an Architecture Decision Record (ADR) in the Decision Log.

Each ADR should describe:

- the decision;
- the rationale;
- alternatives considered;
- implications.

This ensures that future contributors understand why the Design System evolved.

---

# Design Principles

All contributions should remain consistent with the Design Principles described in the Design System.

In particular, the methodology shall remain:

- capability-based;
- technology independent;
- modular;
- reusable;
- human-readable;
- AI-readable.

---

# Repository Structure

The Design System is organised into the following major components:

- `/design-system/` — the normative specification.
- `/templates/` — reusable Blueprint templates.
- `/examples/` — reference implementations.
- `/gpt/` — AI knowledge base.
- `/assets/` — shared visual resources.

---

# Questions

If you are unsure whether a proposed change belongs in the methodology or in an individual Blueprint, favour improving the methodology first.

A stronger Design System results in stronger Blueprints.