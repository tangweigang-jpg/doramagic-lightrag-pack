# AI Context Pack

## Pack Identity

- Upstream: https://github.com/HKUDS/LightRAG
- Pack type: Retrieval-Augmented Generation Context Pack
- Doramagic canonical: https://doramagic.ai/en/projects/lightrag/
- Relationship: independent pack; not affiliated or endorsed unless explicitly stated.

## Operating Rules

- Evidence first.
- No official endorsement claim.
- Run evals before claiming success.
- Use pitfall and risk files for recovery.

## Host Files

- `../AGENTS.md`
- `../CLAUDE.md`

## Doramagic Source Extract

# LightRAG - Doramagic AI Context Pack

> Purpose: pre-work context for the user's host AI. This pack does not prove that the project has been installed, run, or validated.

## Project

- canonical_name: `HKUDS/LightRAG`
- capability: [EMNLP2025] "LightRAG: Simple and Fast Retrieval-Augmented Generation"
- expected_user_outcome: [EMNLP2025] "LightRAG: Simple and Fast Retrieval-Augmented Generation"

## Operating Boundaries

- Do not claim that the project has been installed, run, called through an API, or used on local files unless separate evidence proves it.
- Project facts must come from repo evidence, Claim Graph, or explicit source references.
- When a capability is not verified, mark it as unverified instead of completing it as fact.
- publish_status: `publishable`
- blocking_gaps: none

---

## Doramagic Context Augmentation

The following sections strengthen the repository context for a host AI. Human Manual data is a reading route, and pitfall notes become operating constraints.

## Human Manual Outline

Usage rule: this is only a reading route and salience signal, not factual authority. Concrete claims must still return to repo evidence or Claim Graph.

Host AI hard rules:
- Do not treat page titles, section order, summaries, or importance values as factual project evidence.
- When explaining the Human Manual outline, state that it is only a reading route or salience signal.
- Capability, installation, compatibility, runtime state, and risk claims must cite repo evidence, source paths, or Claim Graph.

- **Overview and System Architecture**: importance `high`
  - source_paths: README.md, lightrag/__init__.py, lightrag/lightrag.py, lightrag/base.py, lightrag/operate.py
- **Core API, Query Pipeline, and Multimodal Processing**: importance `high`
  - source_paths: lightrag/lightrag.py, lightrag/operate.py, lightrag/types.py, lightrag/llm_roles.py, lightrag/prompt.py
- **Storage Backends, Knowledge Graph, and Document Management**: importance `high`
  - source_paths: lightrag/kg/factory.py, lightrag/kg/shared_storage.py, lightrag/kg/json_kv_impl.py, lightrag/kg/json_doc_status_impl.py, lightrag/kg/nano_vector_db_impl.py
- **Deployment, WebUI, Evaluation, and Operations**: importance `high`
  - source_paths: lightrag/api/lightrag_server.py, lightrag/api/config.py, lightrag/api/auth.py, lightrag/api/gunicorn_config.py, lightrag/api/run_with_gunicorn.py

## Repo Inspection Evidence

- repo_clone_verified: true
- repo_inspection_verified: true
- repo_commit: `1c121ace61e3c72f57f813e0f7dbd75a924bd996`
- inspected_files: `uv.lock`, `Dockerfile`, `pyproject.toml`, `README.md`, `docker-compose.yml`, `docs/LightRAG-API-Server.md`, `docs/FileProcessingPipeline.md`, `docs/AdvancedFeatures.md`, `docs/ThirdPartyParser.md`, `docs/UV_LOCK_GUIDE.md`, `docs/ProgramingWithCore.md`, `docs/OfflineDeployment.md`, `docs/LightRAGSidecarFormat.md`, `docs/FrontendBuildGuide.md`, `docs/FileProcessingPipeline-zh.md`, `docs/MilvusConfigurationGuide.md`, `docs/Reproduce.md`, `docs/DockerDeployment.md`, `docs/Algorithm.md`, `docs/LightRAGSidecarFormat-zh.md`

Host AI hard rules:
- Without repo_clone_verified=true, do not claim that the source code has been read.
- Without repo_inspection_verified=true, do not write README, docs, or package-file conclusions as facts.
- Without quick_start_verified=true, do not claim that the Quick Start path has run successfully.

## Doramagic Pitfall Constraints

These rules come from Doramagic discovery, validation, or compilation findings. The host AI must treat them as operating constraints, not background notes.

### Constraint 1: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/HKUDS/LightRAG/issues/2642
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 2: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/HKUDS/LightRAG/issues/2746
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 3: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/HKUDS/LightRAG/issues/3195
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 4: Configuration risk requires verification

- Trigger: Project evidence flags a configuration risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/HKUDS/LightRAG/issues/2502
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 5: Configuration risk requires verification

- Trigger: Project evidence flags a configuration risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/HKUDS/LightRAG/issues/2709
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 6: Capability evidence risk requires verification

- Trigger: Project evidence flags a capability evidence risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/HKUDS/LightRAG/issues/2761
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 7: Runtime risk requires verification

- Trigger: Project evidence flags a runtime risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/HKUDS/LightRAG/issues/2768
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 8: Runtime risk requires verification

- Trigger: Project evidence flags a runtime risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/HKUDS/LightRAG/issues/3234
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 9: Installation risk requires verification

- Trigger: Developers should check this installation risk before relying on the project: [v1.5.0] /query still returns [no-context] due to embedding worker timeout even though embeddings API is reachable and documents exist
- Host AI rule: Before packaging this project, run the relevant install/config/quickstart check for: [v1.5.0] /query still returns [no-context] due to embedding worker timeout even though embeddings API is reachable and documents exist. Context: Observed when using python, docker
- Why it matters: Developers may fail before the first successful local run: [v1.5.0] /query still returns [no-context] due to embedding worker timeout even though embeddings API is reachable and documents exist
- Evidence: failure_mode_cluster:github_issue | https://github.com/HKUDS/LightRAG/issues/3195
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 10: Installation risk requires verification

- Trigger: Developers should check this installation risk before relying on the project: v1.4.10
- Host AI rule: Before packaging this project, run the relevant install/config/quickstart check for: v1.4.10. Context: Observed when using windows
- Why it matters: Upgrade or migration may change expected behavior: v1.4.10
- Evidence: failure_mode_cluster:github_release | https://github.com/HKUDS/LightRAG/releases/tag/v1.4.10
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

