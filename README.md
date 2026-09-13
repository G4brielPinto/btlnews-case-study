# BTLNews — Private Implementation Case Study

BTLNews is an academic project centred on analysing and searching news content in a public-policy
context. This repository records the project at a high level while respecting the boundary between a
portfolio description and a private implementation.

## What this repository contains

- a safe, high-level project description;
- the intended system boundaries and technology themes;
- a clear statement of what is not shared.

It deliberately does not contain the original application source. The source remains in a separate
private codebase that is outside the material available for this portfolio review.

## Solution outline

The academic material describes a web-oriented workflow for:

1. collecting and storing publication records;
2. classifying or tagging content by topic;
3. supporting API-driven access;
4. enabling semantic search over indexed material;
5. presenting results through a web interface.

The implementation was described around a Django and PostgreSQL stack, with vector-based retrieval
for semantic search. This is a historical architecture summary, not a live deployment guide.

## Deliberately excluded

A database backup was found among the supplied project material. It contains sensitive operational
content, including user-account records, password hashes, publication content and vector embeddings.
It is not included, inspected beyond the security triage needed to identify the risk, or uploaded.

The following are also excluded:

- all application code;
- all raw documents and indexed content;
- database schemas and dumps;
- user data, credentials and environment configuration;
- issue trackers, private links and internal reports.

## Status

The repository is intentionally documentation-only. It is kept private until there is an explicit
decision on whether a clean, independently authored demonstrator can be created without reusing
private implementation code or content.

## Attribution

This repository documents an academic team deliverable. It does not attribute individual ownership
of particular components.
