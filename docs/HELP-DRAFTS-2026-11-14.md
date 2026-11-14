# Help article drafts — 2026-11-14

Nine English articles adapted from the local editorial handoffs dated 2026-11-14. They use the existing Markdown/frontmatter format, community blocks from `docs/VOICE.md`, and internal catalogue links. Each article remains `status: draft` and `human_verified: false`.

**Publication is awaiting Andrey's decision.** A local build is not product acceptance. The content loader does not hide draft status: merging these files into a deployed branch would expose them in routes, navigation, search, and SEO output. Do not merge or publish this package before review.

## Review before publication

| Article | Entry pages | Remaining human check |
|---|---|---|
| `/orders/shipping-status-explained/` | Track your order | Operations owner confirms carrier wording and the warehouse/carrier handover route. No new delivery or response-time promises. |
| `/troubleshooting/power-midi-sound/` | No sound; Troubleshooting hub | Product owner follows the recognition → notes → audio checks on a named device, system, and app. |
| `/troubleshooting/connection-drops/` | Troubleshooting hub; Device will not connect | Product owner checks the intermittent-failure route and stopping point on a named board revision. |
| `/software/phone-browser-or-app/` | Mobile apps; Connect your device | Product owner verifies a named phone/system/app/device combination. No universal mobile browser or adapter compatibility claim. |
| `/troubleshooting/firmware-download-vs-installed/` | Firmware recovery | Product owner confirms version-reading availability and the update file/route for the selected board revision. No new contact-bridging or erase instructions. |
| `/software/play-fullscreen/` | Playtron; More instruments | Check both the separate icon and earlier desktop menu route on the release being documented; verify exit behaviour in selected browsers. |
| `/software/play-how-to-play/` | Playtron | Check first recognised connection, reopening, site-local browser storage, and direct sound-pack links on the target release. |
| `/software/biotron-settings-hints/` | Biotron; Settings layout | Check hint controls, labels, and setting-send behaviour with supported firmware; release with the matching Biotron interface. |
| `/software/biotron-settings-layout/` | Biotron; Settings hints | Confirm the compact layout's acceptance and availability on the target release, including narrow screens and preset actions. |

## Version boundaries carried from the handoff

The source handoff was prepared on 2026-11-14. It checked local source code and release records, not the current live sites. No new live-site or hardware verification is claimed here.

- The separate Play **Full screen** icon was documented in a beta after the last recorded production build. Both entry routes remain in the article.
- Play **How to play** and browser-local first-connection storage were also found in the earlier released source `a96c1c6a73b7`.
- Biotron hint and compact-layout text describes the new Biotron interface, not `settings.playtronica.com`. The handoff linked the compact interface to beta `b6eae2277128` and source `1010229`. A prior hint review does not establish acceptance of the later layout.
- UI source snapshot in that handoff: `playtronica-sites` commit `0f7dfdb457b8ce8ec7493f3b97058701fba7e09c`, dated 2026-11-14. This is source provenance, not a production-release claim.

The local result file outside this public repository maps all articles to the original private handoffs. Customer text, personal data, message bodies, and private evidence were not copied into articles or this note. Existing help-loop gaps remain unverified and unchanged.

## Editorial choices and checks

- Support details use question headings without adding response-time promises. Community copy follows the existing voice specification; its membership figure is inherited copy, not a fresh membership count.
- Existing pages receive only links, narrow context, and edit dates. Existing device, delivery, and firmware procedures remain the authority pending their separate review.
- The internal-consistency checker now recognises `biotron.playtronica.com` alongside the existing device sites. This lets the new articles name the correct interface without pointing to the older Settings site.
- Rebuild the existing hypothesis inventory after adding pages. New entries have no publication date or measured outcome. Draft status does not establish either.
- Run `./help check --full` locally. It includes the help-loop tests, content audits, lint, production export, Pagefind indexing, and built-link check. See the local result for actual outcomes and limitations.

No lifecycle status, team board, message, remote branch, or deployment is changed by this editorial package.

Validation on 2026-11-14: `./help check --full` passed, including all help-loop tests, content audits, lint, and the production export. `npm run links:check` passed its offline URL-shape check. A separate local smoke check confirmed all nine article titles, support/community links, search entries, and generated language fallback pages. This does not establish live external-link health, physical-device behaviour, or human product acceptance.
