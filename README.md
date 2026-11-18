# RefundWatch website

Static informational website for RefundWatch, published via GitHub Pages from `main` / root.

## Pages
- `index.html` — Home
- `privacy.html` — Privacy Policy (draft)
- `terms.html` — Terms of Service (draft)
- `support.html` — Support: refundwatch.support@gmail.com

## Before publishing for Plaid / App Store
- [ ] Verify the product descriptions against the deployed iOS app and backend.
- [x] Add the owner-provided support/privacy contact: refundwatch.support@gmail.com.
- [ ] Owner confirms the mailbox is monitored; no response-time commitment is made.
- [ ] Finalize the privacy policy: actual data categories, storage, sharing, retention, deletion, rights, and operator identity.
- [ ] Finalize Terms of Service and obtain legal review as appropriate.
- [ ] Replace placeholder brand mark with approved RefundWatch app icon.
- [ ] Remove draft banners only after review.
- [ ] Confirm public HTTPS access to all four pages.

The legal-page update remains a review draft, not an effective policy or a deployment approval. Operator identity and any required mailing address, final retention decisions (connection history, deletion safeguards, backups and support correspondence), applicable privacy-rights procedures, third-party/App Store disclosures, legal approval and an effective date remain publication blockers. Explicit source comments in `privacy.html` and `terms.html` track these decisions. Keep both draft banners until those decisions are resolved.

The pages describe the reviewed iOS/backend source at `56d2672c7bdf50655015a40114551dea2beb35a7`. Source inspection does not establish that every deployed component or App Store Connect disclosure matches that revision. The PR records the technical claim verification and validation evidence.

No secrets, Plaid tokens, Firebase configuration, or user data belong in this repository.
