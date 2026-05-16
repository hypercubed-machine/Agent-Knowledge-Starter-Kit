# OpenSpec Integration Guide

This guide provides instructions on how to integrate OpenSpec agents with the Agent Knowledge Starter Kit (AKSK). OpenSpec agents are designed to follow spec-driven development and can effectively utilize the knowledge base established by AKSK.

## Guidelines for OpenSpec Agents

- **Read, Don't Execute:** OpenSpec agents must read and understand the `SKILL.md` files within the AKSK project. They are not to execute these as scripts directly.
- **Rule Enforcement:** Agents should scan the `openspec.yaml` configuration and apply the defined rules.
- **Durable Knowledge:** Use the AKSK knowledge capture cycle: propose changes, get approval, execute, and distill results.

## Configuration Requirements

Ensure your OpenSpec configuration includes directives that point to the `docs/integrations/` directory, treating it as the primary documentation source for agent behavior when interacting with AKSK.
