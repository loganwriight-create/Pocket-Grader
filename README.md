# Pocket Grader

Updated prototype with a card-specific eBay UK sold-listings search in the Value tab. Search terms are built from card name, set/number, language and selected grade. The prototype still requires manual entry of sold prices to calculate a market average.

## Publish with GitHub Pages
1. Create a public repository named `pocket-grader`.
2. Upload all files in this folder to the repository root.
3. In Settings → Pages, choose Deploy from a branch, `main`, and `/(root)`.
4. Open the published URL in Safari and add it to your Home Screen if desired.

## Important limitations
- This is a prototype, not a production AI grader.
- Automatic card recognition, centering measurement and condition grading are not implemented.
- eBay sold search opens matching completed listings; sold prices are not imported automatically. eBay's official Marketplace Insights API is limited-release and requires approval. A secure server-side integration and approved API access are needed for in-app automatic sold data.
