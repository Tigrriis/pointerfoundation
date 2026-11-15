# pointerfoundation.org

Placeholder "coming soon" site for Pointer Foundation. Plain static HTML with no build step.

## Deploying on Cloudflare Pages

1. In the Cloudflare dashboard, go to **Workers & Pages → Create → Pages → Connect to Git** and pick this repository.
2. Build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/`
3. Deploy, then under **Custom domains** add `pointerfoundation.org` (and `www.pointerfoundation.org` if you want it).

Every push to the production branch redeploys automatically.

## Brand

The page shares PointerPath's brand: the logomark on an amber tile, Outfit SemiBold for the heading and Inter for body text (both loaded from Google Fonts), and the same ink, paper and amber colours. The source files and usage rules are in the `brand/` folder of the `pointerturn` repository.
