---
title: "What is CML:AUS?"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# What is CML:AUS?

## Overview

Common Modeling Language: A Universal Schema (CML:AUS) defines methods of communication across data systems and data ecosystems. CML:AUS is intended to be supported by a variety of tools as an eventual standard after sufficient time for comment, iteration, and revision.

### CML:AUS described data systems, data ecosystems, and their components including:
- sources (media interfaces/specs - e.g. data warehouses, users, databases, applications, images, video, audio, etc.)
- targets (media interfaces/specs - e.g. data warehouses, users, databases, applications, images, video, audio, etc.)
- storage (media - e.g. data warehouses, block storage, databases, files, etc.)
- stage (e.g. dev, production, etc.)
- transformations (i.e. algorithms)
- types (i.e. schemas or data models)
- interfaces (i.e. scope boundaries, APIs, UIs)

### CML:AUS is a meta-language. It can be expressed in multiple formats including:
- YAML
- TOML
- JSON
- XML
- EDN
- or even a collection of CSVs

### CML:AUS is based on a data model of distributed directed graphs and vectorized operations.

## Goals of CML:AUS

### CML:AUS maps to nearest neighbor using vectorized clustering for resource-optimized refactoring of data ecosystems.

## CML:AUS Definitions

### CML:AUS definitions are able to reference internal and external CML:AUS definitions or resources (i.e. entities/instances)
- Internal references
  - Referenced using URN
- External references
  - Referenced using URN with URL
- Both reference types (internal and external) use a common "ref" form described for each language used (YAML/JSON/XML/etc.)

### CML:AUS definitions of transformations:
- in some cases may only include conceptual steps
- or they could include the actual implementation (or versions of it),
- or they could contain both.
- Transformations are any form of descriptions of algorithms.

### CML:AUS templates should be self-documenting through:
- external references
- internal references
- clear definitions
- clear naming conventions
- "docs" property/attribute method (i.e. docs as data)

### Every CML:AUS definition and reference should include an absolute version, but it can also include:
- a relative version
- version group
- one or more patterns

### CML:AUS definitions can reference external files that are not CML:AUS
- this requires at least that at a minimal CML:AUS definition has been defined and referenced (either inline or via a secondary reference)

### CML:AUS definitions can inherit or import from multiple other CML:AUS definitions
- Each inheritance or import statement is itself a "ref" statement and it overwrites prior inheritance statements if the namespace overlaps.
- Can explicitly exclude or include subsets.
- Use a namespace or alias to avoid overlap within a definition.

