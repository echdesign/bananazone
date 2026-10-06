# BananaZone Casino Edition landing page

Responsive operator/aggregator landing page with the original dark and Candy Zone artwork extracted from the supplied design PDF. The private MSA is not included in the website or public assets.

## Development

Node.js 20.19+ or 22.12+ is required by Vite.

```sh
npm ci
npm run dev -- --port 5173
```

Production: `npm run build`. Serve `dist/` on a static host. Both `/` and `/demo.html` are build entries.

## Deploy on Netlify

In Netlify, choose **Add new project → Import an existing project → GitHub**, then select `echdesign/bananazone` and the `main` branch. The included `netlify.toml` configures Node 24, the `npm run build` command and the `dist` publish directory. Leave the base directory empty and deploy. Netlify supplies the public site URL when the deployment completes.

To download files instead, use GitHub's **Code → Download ZIP** for the source, then run `npm ci` and `npm run build` locally. Upload the generated `dist` folder for a manual Netlify deployment.

## Before publishing

Set the actual dark/Candy operator demo URLs, Calendly URL, contact email, and approved Jackpot Studios logo URL in `site-config.js`. Empty demo URLs open the local interactive concept, clearly labelled as illustrative and uncertified. Empty contact destinations show an honest preview notice rather than submitting or inventing contact details.

The local concept is not the production game: three illustrative bands, fixed example multipliers, browser-generated outcomes, and demo credits only. It implements selection, a three-second confirmation window, five-second settlement, and reset. Official demos replace it when configured.

Branding uses the supplied BananaZone SVG and #FFEC42 yellow. Partner branding uses the Jackpot logo supplied by the user.

Public copy is drawn from MSA product scope, not private commercial terms. Certification is qualified as provider internal certification plus requirements under its Anjouan B2B licence. No external laboratory approval or fixed RTP is claimed. The under-two-week timeline supplied by the user is an operator integration target for a release-ready game, subject to readiness and approvals; the MSA separately estimates initial development at 3–5 weeks. Confirm release and certification status, territory eligibility, timeline, and partnership announcement approval before public release.

Screenshots are design concepts. Their Bitcoin-labelled UI is reproduced from the provided deck; public copy clarifies that the production Banana Index is fictional, not a live financial market.
