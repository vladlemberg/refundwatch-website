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
- [ ] Owner confirms the mailbox is monitored. Support target: initial response within 2 business days (a goal, not a guarantee).
- [x] Public operator contact (PO decision 2026-11-19): Astora LLC, Colorado, United States, and refundwatch.support@gmail.com. No residential address is published; legal sufficiency pending legal/compliance review.
- [ ] Finalize the privacy policy: legal review and App Store privacy-answer reconciliation.
- [ ] Finalize Terms of Service and obtain legal review as appropriate.
- [ ] Replace placeholder brand mark with approved RefundWatch app icon.
- [ ] Remove draft banners only after review.
- [ ] Confirm public HTTPS access to all four pages.

The legal pages remain review drafts, not an effective policy or a deployment approval. Retention decisions and the deletion-marker expiry are incorporated. Third-party/App Store disclosure reconciliation, legal review, Product Owner approval and an effective date remain publication blockers. Explicit source comments in `privacy.html` and `terms.html` track these decisions. Keep both draft banners until those decisions are resolved.

The original legal audit reviewed iOS/backend source at `56d2672c7bdf50655015a40114551dea2beb35a7` (audit baseline). The deletion-marker expiry described in Privacy §9 comes from the later implementation at `a68891f60161edd666e141dfdf37b0232439511d` (refund-watch PR #34); see audit §12. Source inspection does not establish that every deployed component or App Store Connect disclosure matches these revisions. The PR records the technical claim verification and validation evidence.

Publication evidence: [LEGAL-PUBLICATION-AUDIT.md](LEGAL-PUBLICATION-AUDIT.md) records the November 18, 2026 source, Release-manifest and retention review. Its recommendation is **NOT READY**. Resolve the documented owner/legal and disclosure blockers before treating Privacy Policy v1.0 or Terms of Service v1.0 as effective.

No secrets, Plaid tokens, Firebase configuration, or user data belong in this repository.
