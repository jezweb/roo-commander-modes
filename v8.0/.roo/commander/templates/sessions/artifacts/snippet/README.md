# Session Artifacts: Snippets

## Purpose

This directory stores **useful code snippets, configuration blocks, or commands** generated or referenced during the parent session.

These artifacts capture key information like decisions, learnings, environment details, research findings, code snippets, errors, etc., providing richer context beyond the main session log.

See the main guidelines document for details on standard artifact types and their purpose:
[`.roo/rules/03-session-management-standard.md`](.roo/rules/03-session-management-standard.md)

## File Naming Convention

Files should generally follow the convention: `SNIPPET-[Topic]-[YYMMDDHHMM].[ext]`

*   `[TYPE_PREFIX]`: `SNIPPET` for this directory.
*   `[Topic]`: A short, descriptive, filesystem-safe topic (e.g., `fetch_data_hook`, `dockerfile_example`).
*   `[YYMMDDHHMM]`: Timestamp of creation.
*   `[ext]`: Appropriate file extension (e.g., `.md`, `.py`, `.json`, `.sh`).

**Consult the main guidelines document linked above for the specific prefix and conventions recommended for this directory.**

## Recommended Templates

If applicable, use the relevant TOML+MD template from [` .roo/commander/templates/sessions/artifacts/`](.roo/commander/templates/sessions/artifacts/) (e.g., [`template_00_session_snippet.md`](.roo/commander/templates/sessions/artifacts/snippet/template_00_session_snippet.md)).

## Usage

*   Create artifacts here as needed during the session.
*   Ensure the artifact file path (relative to the session directory, e.g., `artifacts/snippets/SNIPPET-fetch_data_hook-2506050200.md`) is added to the `related_artifacts` array in the main `session_log.md`.

## User Contribution

Users can manually add relevant files to this directory, following the naming conventions specified in the main guidelines document.