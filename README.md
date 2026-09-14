# A_My_Island

A_My_Island turns an Obsidian vault into an interactive island workspace with graph-based planning, tables, character scenes, phone apps, mail, and personal dashboards.

## Platform

This plugin is desktop-only because optional features use desktop APIs for local file selection, media, and mail connectivity.

## Licensing and payment

A_My_Island is closed-source commercial software. Full access requires a valid paid license. The source is maintained in a private repository and is made available to the Obsidian Community Directory review system for source and reproducible-build verification.

The proprietary license for A_My_Island is in `LICENSE`. Third-party licensing information for Cytoscape.js is in `THIRD_PARTY_LICENSES.md`; that MIT License applies only to Cytoscape.js and does not license this plugin as a whole.

## Network access

Depending on the features used, the plugin may connect to:

- the A_My_Island licensing service for activation and periodic license verification;
- GitHub Releases for optional, non-executable static image, animation, dialogue, and scene resources;
- a weather endpoint explicitly configured by the user;
- email providers configured by the user, including their IMAP servers and remote images contained in messages;
- websites explicitly opened by the user in the phone video or browser-style interfaces.

The plugin does not download or execute remote JavaScript as an update mechanism. Static resource archives are restricted to the official release repository and are verified by package identity, path allowlists, file sizes, and SHA-256 hashes before installation.

## Local and external files

Plugin data is stored in the user's vault. The plugin accesses files outside the vault only after an explicit user action such as selecting an image, choosing an export folder, or importing local media. It does not scan unrelated external directories.

## Privacy

The plugin does not contain client-side telemetry, behavioral analytics, or advertising. License activation sends the entered license key, product code, locally generated device identifier, device label, and platform to the licensing service. Optional online features transmit only the information required for the feature selected by the user.

See `PRIVACY.md` for details.

## Installation

Install the plugin through the Obsidian Community Plugins directory after approval. Release assets are published in the public A-My-Island-Releases repository.

## Optional static resources

This repository also distributes optional, non-executable PNG, WebP, and Markdown resource packages used by A_My_Island. `resources/core-assets/latest.json` points to the latest immutable resource manifest. The plugin verifies the official GitHub source, package identity, allowed paths, file sizes, and SHA-256 hashes before installing a package. Vault notes and user records are not uploaded.

Users who cannot access GitHub can obtain the resource archive through the support channel and extract its resource directories beside the standard plugin files under `.obsidian/plugins/a-my-island/`.

This plugin uses Cytoscape.js, licensed under the MIT License. See `THIRD_PARTY_LICENSES.md` for details.
