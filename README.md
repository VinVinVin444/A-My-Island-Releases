# A-My-Island-Releases

Public static-resource releases for the closed-source commercial Obsidian plugin **A_My_Island**.

## Scope

- This repository distributes non-executable static resources only, such as PNG, WebP, and Markdown templates.
- Resource packages do not contain JavaScript, plugin code, or executable update logic.
- The plugin downloads resources only after validating the GitHub source, package ID, paths, sizes, and SHA-256 hashes.
- No user Vault records are uploaded.

## Resource index

- `resources/core-assets/latest.json` points to the latest immutable core-assets manifest.
- Versioned ZIP archives and manifests are attached to GitHub Releases.

## Manual installation

Users who cannot access GitHub may download the resource ZIP manually and place its extracted resource directories beside the plugin's standard files under:

`.obsidian/plugins/a-my-island/`

## License

A_My_Island remains closed-source commercial software. Publication of these resources does not grant permission to copy, redistribute, modify, or reuse them unless a specific file states otherwise.

Cytoscape.js license information for the plugin is provided in `THIRD_PARTY_LICENSES.md`.
