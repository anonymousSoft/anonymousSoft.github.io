# anonymoussoft.github.io

Public pages for anonymoussoft apps, served by GitHub Pages from the
`anonymousSoft/anonymousSoft.github.io` repository. The source lives in the
BabySteps repo under `site/`; copy changes there and push to the Pages repo.

| Page | URL |
|---|---|
| BabySteps home | https://anonymoussoft.github.io/babysteps/ |
| Privacy policy | https://anonymoussoft.github.io/babysteps/privacy.html |
| Terms of use | https://anonymoussoft.github.io/babysteps/terms.html |
| Account deletion | https://anonymoussoft.github.io/babysteps/delete-account.html |
| Invite links (Android App Link) | https://anonymoussoft.github.io/join?code=XXXXXXXX |
| App Link verification | https://anonymoussoft.github.io/.well-known/assetlinks.json |

`.nojekyll` makes GitHub Pages serve the `.well-known` folder.

`assetlinks.json` lists the EAS upload key. After the first Play upload, add
the **Play app-signing** SHA-256 (Play Console > Test and release > App
integrity) to `sha256_cert_fingerprints`, otherwise invite links from the
Play Store build open in the browser instead of the app.
