# Zotero Title Normalizer

Clean up bibliography titles without losing control of the changes.

**Zotero Title Normalizer** is a desktop plugin for **Zotero 6, 7, 8, 9, and 10**.
Its goal is to make imported titles readable and consistent by fixing common
whitespace, HTML entity, and Unicode problems, and converting a curated set of
physics LaTeX expressions into readable text.

| Before | After normalization |
| --- | --- |
| `$H \to \gamma\gamma$` | H → γγ |
| `$\sqrt{s}=13~\mathrm{TeV}$` | √s = 13 TeV |
| `A&nbsp;result &amp; discussion` | A result & discussion |

## Review and recover changes

The official release previews each batch before saving. Review selected items,
an entire library, or newly added titles, then apply only the proposals you want.
Unknown equations and existing rich-text markup are preserved; unsupported math
is flagged for review. The tool does not standardize capitalization or evaluate
arbitrary LaTeX.

**Restore previous titles** recovers the latest applied batch. Later manual edits
and changed permissions are treated as conflicts instead of being overwritten.
Normalization runs locally, without sending titles to an external normalization
service. Zotero's own synchronization still applies to saved changes.

## Zotero versions covered

The official **v0.1.1** distribution provides a separate installer for each major
version. Choose the one matching **Help → About Zotero**.

| Zotero desktop version | Official installer | Recorded macOS desktop test |
| --- | --- | --- |
| 6.0.x | [Zotero 6](https://github.com/Zotero-Title-Normalizer/zotero-title-normalizer/releases/tag/v0.1.1-zotero6) | 6.0.37 |
| 7.0.x | [Zotero 7](https://github.com/Zotero-Title-Normalizer/zotero-title-normalizer/releases/tag/v0.1.1-zotero7) | 7.0.21 |
| 8.0.x | [Zotero 8](https://github.com/Zotero-Title-Normalizer/zotero-title-normalizer/releases/tag/v0.1.1-zotero8) | 8.0.5 |
| 9.0.x | [Zotero 9](https://github.com/Zotero-Title-Normalizer/zotero-title-normalizer/releases/tag/v0.1.1-zotero9) | 9.0.6 |
| 10.0.x | [Zotero 10](https://github.com/Zotero-Title-Normalizer/zotero-title-normalizer/releases/tag/v0.1.1-zotero10) | 10.0.6 |

Desktop smoke tests were recorded on macOS on **October 22, 2026**. Windows and
Linux have not been desktop-tested. These results cover the recorded versions,
not every patch release or future Zotero major version.

## Get the plugin

The [official distribution](https://github.com/Zotero-Title-Normalizer/zotero-title-normalizer)
and [development repository](https://github.com/Zotero-Title-Normalizer/zotero-title-normalizer-dev)
are currently **private**. Their source, documentation, issue trackers, and release
downloads require GitHub access to the respective repository. This public profile
describes the project; it does not provide public installer downloads.

If you have access, download the matching `.xpi` from its release page and install
it through Zotero's Tools → Plugins/Add-ons → gear menu → Install From File.
Install only one variant per Zotero profile. Updates are installed manually.

See the official repository for installation details, compatibility evidence,
recovery instructions, and issue reporting. Development candidates may include
features that have not yet shipped in the official release.

This is a community plugin and is not an official Zotero product.
