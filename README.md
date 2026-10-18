# Chess Prodigy: Tactical 3D — legal documents

Developer: mitkonaft games. Bundle: `com.mitkonaft.chessprodigy`. Apple ID: `6823743809`.

- Privacy policy: https://mitkonaft.github.io/chess-prodigy-legal/
- Stockfish source and license: https://github.com/mitkonaft/chess-prodigy-legal
- Support and source requests: mitkonaft@gmail.com

## Stockfish source distribution and source offer

The included Stockfish 19 chess engine is distributed under GNU GPL version 3 or, at your option, any later version, as specified in its source notices. The full GPLv3 text is in `stockfish-license/LICENSE.txt`; upstream copyright notices and AUTHORS are preserved. The developer-supplied Stockfish configuration and bridge in this source package are provided under GPLv3-or-later, with existing notices preserved. This does not relicense third-party SDKs or unrelated application assets.

Use https://github.com/mitkonaft/chess-prodigy-legal or download this repository with GitHub **Code → Download ZIP**. The package contains the actual Stockfish sources from the current app workspace, local configuration, Objective-C++ bridge, build settings, and the exact NNUE file. `stockfish-license/SHA256SUMS` identifies every packaged file. See its README for rebuilding and integration details.

mitkonaft games offers recipients access at no charge to the corresponding Stockfish engine source and local modifications through this repository. If the download is unavailable, email ak.onfire@mail.ru with the app version/build to request an electronic copy at no charge. We will honor this source offer for at least three years after the last distribution of the corresponding build, and longer where GPLv3 requires it. Preserve version-specific source snapshots when shipping updates.

**Scope:** This repository publishes the engine package, not the complete application source. Stockfish is linked into the app. An engine-only source package and this offer do not establish fulfillment of any GPL obligations for the combined application. Before distributing a binary, resolve those obligations, provide all required corresponding source/build instructions, and confirm compatibility of all linked components. The snapshot here has not been matched to an App Store binary archive.

## GitHub Pages

Enable Settings → Pages → Deploy from a branch → `main` → `/ (root)`. The root `.nojekyll` file supports plain static HTML. Verify both public URLs return the actual documents before entering them in App Store Connect. A successful git push alone does not enable Pages.

The privacy policy reflects the inspected app implementation; it does not certify SDK consent configuration, App Store disclosures, or production release readiness.
