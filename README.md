# CoGAP Research Skill

A portable Agent Skill for interpreting evidence returned by an authorized CoGAP MCP service: disease-pair coverage, stored Mendelian randomization results, shared genes, expression summaries, stored risk models and literature retrieval.

The skill helps an agent choose relevant tools and preserve provenance, uncertainty and scientific identifiers. The connected service supplies the evidence.

## Contents

- [Skill instructions](skills/cogap-research/SKILL.md)
- [MCP connection requirements](skills/cogap-research/references/mcp-connection.md)

## Use

Copy the `skills/cogap-research` directory into the skill discovery location supported by your agent client. Confirm the client's current installation and discovery instructions. The skill follows the [Agent Skills specification](https://agentskills.io/specification).

Connect an operator-authorized CoGAP MCP service using the linked connection requirements. Installing the skill alone does not provide a server, endpoint, credentials or dataset. A public hosted CoGAP endpoint is not supplied by this repository.

Then request CoGAP evidence or explicitly ask the agent to use `cogap-research`. Verify a real tool call before treating an answer as database-backed.

## Scope

This repository distributes only the skill and connection documentation. It does not distribute the website, backend implementation, database, user histories, uploaded material, credentials or scientific datasets. The license applies to these skill files and documentation; access to service data remains subject to its operator's terms.

See [LICENSE](LICENSE) for the MIT license.
