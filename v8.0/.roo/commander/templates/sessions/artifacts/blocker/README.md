# Session Artifacts: Blockers

## Purpose

This directory stores **details about specific obstacles encountered and potential solutions** during the parent session.

These artifacts capture key information like decisions, learnings, environment details, research findings, code snippets, errors, etc., providing richer context beyond the main session log.

See the main guidelines document for details on standard artifact types and their purpose:
[`.roo/rules/03-session-management-standard.md`](.roo/rules/03-session-management-standard.md)

## File Naming Convention

Files should generally follow the convention: `BLOCKER-[Topic]-[YYMMDDHHMM].md`

*   `[TYPE_PREFIX]`: `BLOCKER` for this directory.
*   `[Topic]`: A short, descriptive, filesystem-safe topic (e.g., `api_authentication_issue`, `dependency_conflict`).
*   `[YYMMDDHHMM]`: Timestamp of creation.
*   `[ext]`: `.md` is recommended.

**Consult the main guidelines document linked above for the specific prefix and conventions recommended for this directory.**

## Recommended Templates

If applicable, use the relevant TOML+MD template from [` .roo/commander/templates/sessions/artifacts/`](.roo/commander/templates/sessions/artifacts/) (e.g., [`template_00_session_blocker.md`](.roo/commander/templates/sessions/artifacts/blocker/template_00_session_blocker.md)).

## Usage

*   Create artifacts here as needed during the session.
*   Ensure the artifact file path (relative to the session directory, e.g., `artifacts/blockers/BLOCKER-api_authentication_issue-2506050100.md`) is added to the `related_artifacts` array in the main `session_log.md`.

## User Contribution

Users can manually add relevant files to this directory, following the naming conventions specified in the main guidelines document.