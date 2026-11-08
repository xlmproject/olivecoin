OLIVE (OLV) Cloudflare Pages bundle

Files:
- index.html: responsive static website
- olive.png: generated token artwork/logo
- stellar.toml: Stellar asset metadata at /stellar.toml
- .well-known/stellar.toml: metadata mirror
- _headers: CORS and basic security headers

Deployment:
1. Upload this folder to a new Cloudflare Pages project using Direct Upload, or connect its Git repository.
2. For a static HTML site, leave the build command empty and set the output directory to the project root ( / ).
3. Attach olivecoin.pages.dev to the project.
4. After deployment, check:
   https://olivecoin.pages.dev/
   https://olivecoin.pages.dev/olive.png
   https://olivecoin.pages.dev/stellar.toml
   https://olivecoin.pages.dev/.well-known/stellar.toml

The trade link opens the StellarTerm OLV/XLM market route. The market may not have offers or liquidity.
The displayed price is the user-provided reference value and is not fetched from a live market feed.
The asset code OLV was selected as a short ticker because no ticker was specified.
