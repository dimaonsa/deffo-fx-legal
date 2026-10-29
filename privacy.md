# DEFFO FX — Privacy Policy

Effective date: 29 october 2026

Developer: Dmitriy Eremeev

Contact: eremeevdm4@gmail.com

## Scope

This policy describes the offline version of the DEFFO FX plugin for Figma. It does not cover Figma's own account, cloud storage or service operations, which are governed by Figma's policies.

## Processing your artwork

The plugin reads the objects you choose to work on, including geometry, text, font information, visual properties and node references, to calculate and display deformations. It may inspect surrounding document structure to position results and recover its saved drafts.

This processing takes place within the Figma plugin environment. This version makes no network requests and does not upload your artwork to the developer or an external rendering service.

## Information stored by the plugin

The plugin uses storage provided by Figma:

- **Document storage:** draft geometry, deformation settings, node references and recovery metadata may be saved as plugin data in the Figma file. Original objects remain hidden in the file while an unapplied draft exists.
- **Client storage:** named presets, copied deformation settings and interface preferences are saved using Figma's clientStorage.
- **Temporary memory:** active previews, calculations and editing history are held while the plugin runs. Recovery data may also persist in the document.

Document data remains subject to the file's access permissions and Figma's synchronization and retention behavior. Hidden layers are part of the document; hiding a layer is not a privacy boundary against other people with file access.

## Accounts, tracking and sharing

This version has no separate user account or payment login. It does not ask for passwords or payment details. It does not use advertising trackers, remote usage analytics or remote crash reporting. The plugin does not sell or transmit document content to the developer.

If you contact support voluntarily, information you choose to send is handled through the selected email or support service. Avoid sending confidential documents unless necessary. The developer must publish the chosen support channel and its applicable handling terms before this draft becomes effective.

## Managing stored information

- Use **Reset** on a pending draft to restore its original geometry and remove that draft's temporary result and recovery record. Text edits are retained.
- Use **Apply** to commit the vector result. The corresponding hidden original and draft recovery record are removed; the applied artwork remains in the file.
- Use **Delete** in the preset list to remove a named preset.
- Other preferences and copied settings can remain in Figma's client storage. This version does not provide a single clear-all-storage control.

These actions do not erase Figma's document version history or backups. Removing the plugin should not be treated as a guarantee that document data or all preferences have been erased. The developer has no server copy of your artwork or presets to delete on your behalf.

## Changes

This policy must be updated before introducing external licensing, authentication, payments, analytics or other network services. The effective date above identifies the published policy version.

## Contact

For questions about the plugin's data handling, contact eremeevdm4@gmail.com

---
