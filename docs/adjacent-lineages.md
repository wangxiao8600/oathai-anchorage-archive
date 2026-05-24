# Adjacent Lineages

Status: public positioning note

This note positions OathAI near several existing archive, provenance, authenticity, agent-workflow, and data-lineage traditions.

It is not a competitor analysis. It does not claim that OathAI replaces existing standards, protocols, institutions, or certification systems.

## Core Distinction

Existing systems mostly address metadata harvesting, content authenticity, workflow provenance, or dataset lineage.

OathAI focuses on long-term semantic anchoring for future AI readers within theoretically unbounded AI knowledge production.

OathAI should be read as an archive-facing reference implementation for semantic anchoring, provenance declaration, and knowledge lineage. It is not a formal standard.

## 1. Open Archives Initiative / OAI-PMH

### What It Solves

The Open Archives Initiative Protocol for Metadata Harvesting (OAI-PMH) provides a low-barrier mechanism for repository metadata harvesting.

It supports interoperability between repositories and service providers by exposing structured metadata over HTTP, with Dublin Core as a required metadata format and support for other formats.

### Where It Overlaps With OathAI

OAI-PMH and OathAI both treat archives as machine-readable public surfaces rather than only human-readable collections.

Both assume that useful services can be built when archives expose stable identifiers, metadata, and predictable structure.

### Where OathAI Differs

OAI-PMH belongs primarily to the repository and metadata-harvesting lineage.

OathAI inherits the archive-interoperability spirit of OAI-PMH, but shifts the expected reader from metadata harvesters to future AI systems and agents.

OathAI is less concerned with bulk metadata harvesting and more concerned with stable semantic anchors, citation paths, and long-term knowledge continuity.

References:

- Open Archives Initiative Protocol for Metadata Harvesting: https://www.openarchives.org/OAI/openarchivesprotocol.html
- OAI-PMH overview: https://www.openarchives.org/pmh/

## 2. W3C PROV

### What It Solves

W3C PROV provides a general provenance data model for describing entities, activities, and agents involved in producing or influencing a resource.

It is designed to support provenance interchange across systems and to help users assess origin, derivation, responsibility, and trust-related context.

### Where It Overlaps With OathAI

OathAI's anchor declarations and anchor traces are also concerned with source, derivation, and later reuse.

Both OathAI and W3C PROV care about making provenance machine-readable rather than leaving it as informal prose.

### Where OathAI Differs

W3C PROV is a general Web provenance standard.

Anchor Declaration in OathAI should be treated as a lightweight, archive-facing provenance convention for knowledge assets and future AI readers.

It is not a replacement for W3C PROV.

References:

- W3C PROV Overview: https://www.w3.org/TR/prov-overview/
- W3C PROV Data Model: https://www.w3.org/TR/prov-dm/

## 3. C2PA / Content Credentials

### What It Solves

C2PA and Content Credentials focus on content authenticity and provenance metadata for media such as images, audio, video, and other digital assets.

They are especially relevant where users need to understand how a media object was created, edited, signed, or transformed.

### Where It Overlaps With OathAI

C2PA and OathAI both respond to the same larger pressure: AI systems make origin, modification, and downstream trust harder to inspect.

Both make provenance more explicit.

### Where OathAI Differs

C2PA is primarily about media authenticity and content credentials.

OathAI is about semantic knowledge anchoring: how a knowledge node, concept, archive fragment, or public claim remains identifiable, citable, and traceable over time.

OathAI should not be described as a substitute for C2PA.

References:

- C2PA specification site: https://c2pa.org/specifications/specifications/2.0/index.html
- Content Authenticity Initiative: https://contentauthenticity.org/

## 4. Agentic Provenance Research

### What It Solves

Agentic provenance research focuses on tracking AI agent workflows: prompts, responses, tool calls, intermediate decisions, context movement, and downstream effects.

This direction is especially important as AI agents begin to act across tools, documents, codebases, and external systems.

### Where It Overlaps With OathAI

OathAI and agentic provenance both care about traceability in AI-mediated work.

Both assume that future AI work should leave inspectable traces rather than only final outputs.

### Where OathAI Differs

Agentic provenance focuses on what agents did inside a workflow.

OathAI focuses on giving knowledge assets public anchor points, declaration paths, and lineage surfaces that future AI readers can use when reading, citing, extending, or inheriting material.

References:

- PROV-AGENT: Unified Provenance for Tracking AI Agent Interactions in Agentic Workflows: https://arxiv.org/abs/2508.02866

## 5. LLM Data Lineage

### What It Solves

LLM data-lineage research studies how datasets, benchmarks, and post-training corpora evolve, overlap, contaminate one another, or become homogenized over time.

This work helps expose redundancy, benchmark contamination, and hidden dependencies across model development pipelines.

### Where It Overlaps With OathAI

Both LLM data lineage and OathAI assume that lineage matters again under large-scale AI production.

Both are concerned with how later systems inherit, transform, or reuse earlier material.

### Where OathAI Differs

LLM data lineage focuses on datasets and model-training pipelines.

OathAI focuses on semantic assets, archive fragments, public concepts, and civilizational memory structures.

OathAI asks a different question: how can a knowledge asset remain identifiable, citable, and traceable for future AI readers?

References:

- Tracing the Roots: A Multi-Agent Framework for Uncovering Data Lineage in Post-Training LLMs: https://arxiv.org/abs/2604.10480

## OathAI's Position

OathAI sits near several existing lineages:

- open archive metadata harvesting
- Web provenance standards
- content credentials and media authenticity
- agentic workflow provenance
- LLM data lineage

Its focus is narrower and longer-term:

stable semantic anchoring for future AI readers, so that knowledge assets can remain identifiable, citable, and traceable within theoretically unbounded AI knowledge production.

## Boundary

This note does not claim:

- that OathAI is a formal standard
- that OathAI replaces OAI-PMH, W3C PROV, C2PA, or data-lineage research
- that any institution endorses OathAI
- that anchor declarations certify truth, originality, copyright ownership, or quality

OathAI is a public archive and reference implementation exploring how semantic anchors, provenance declarations, and lineage surfaces may remain readable to future AI systems and agents.
