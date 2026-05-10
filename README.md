# Asset Validator & Exporter
In-development Python tool for validating and exporting 3D assets across Blender and Maya.
Part of a Technical Artist transition portfolio (2026).
## Challenge
3D asset pipelines accumulate inconsistencies (ngons, missing UVs, wrong naming, unapplied
transforms) that cause engine issues downstream. Manual review is slow and error-prone.
## Solution
A configurable, cross-DCC validation tool that automates checks, fixes safe issues, and
exports clean assets. Single source of truth in JSON; same logic runs in Blender and Maya.
## Status
Active development — see SESSIONS.md for log.