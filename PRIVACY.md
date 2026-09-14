# Privacy Policy

Last updated: 2026-09-14

## Local data

A_My_Island stores island, graph, table, character, window, cache, and feature settings in the user's Obsidian vault or Obsidian-managed plugin storage. The plugin does not provide the developer with general access to the user's vault.

## Network requests

The plugin makes network requests only for features that require them:

- License activation and verification send the license credential or signed offline-license token, product code, a locally generated device identifier, device label, and platform to the A_My_Island licensing service.
- Static-resource installation reads version metadata and downloads non-executable resource archives from the public A-My-Island-Releases GitHub repository. Vault notes and user records are not uploaded during this process.
- Weather requests are sent to the endpoint and coordinates configured by the user.
- Mail features connect to accounts configured by the user and may download message content, attachments, and remote message images when the corresponding options are enabled.
- Web-based phone features connect only to sites selected or configured by the user.

## Credentials

Mail passwords, provider authorization codes, and tokens are handled through the plugin's credential-storage integration and are not intentionally written in plain text to ordinary island data files. License state is stored in Obsidian-managed plugin data so licensed features can be verified locally.

## Telemetry and advertising

The plugin does not include client-side telemetry, behavioral analytics, or advertising. Operational responses produced by remote services may be processed only to complete the requested feature and display its status.

## External file access

The plugin reads or writes outside the vault only after explicit user actions such as selecting an import file or export folder. It does not scan unrelated external directories.

## Contact

For privacy questions, contact the author through the support channels published with A_My_Island.
