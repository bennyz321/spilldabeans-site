# spilldabeans-site

GitHub Pages site for https://spilldabeans.com (custom domain). /join/ is the in-app Pod invite landing page (task_1791215355609_17412676). /privacy/ and /terms/ are copies of the legal pages (the older copies stay up because app build 470 links to them).

## Home page art (assets/img)

Resized copies of the app's own art (no new art). Source: the iOS app repo at commit 0aba4834 (build 470), the app target's `Assets.xcassets`. Each file was resized with `sips -Z <px>` (keeps alpha, aspect 1:1) to about 2x its largest displayed CSS width, then re-saved losslessly with Pillow (`optimize=True`).

| Site file | App source | Source sha256 | Size |
|---|---|---|---|
| bean-blue.png | welcome-bean-blue.imageset/04-blue-dance-01-front.png | 9d0172c890f19f731a52fa1b1edc4e0ca669f423629d18bc1ce4b5024d156b45 | 1024 -> 808 px |
| bean-orange.png | welcome-bean-orange.imageset/03-orange.png | ec52811f5de6785af99a51bfa628ccde37f22335bf2f4c7f987b00987fe11d71 | 1024 -> 802 px |
| bean-pink.png | welcome-bean-cherry.imageset/01-pink-dance-01.png | 0f05cad3ec3ba65f7086e13c615c2b6b64c2c8dfa6f137b31ac786b0b8df1e78 | 1024 -> 880 px |
| wordmark.png | welcome-wordmark.imageset/spill-da-beans-logo.png | 23fc584c84963965af57ccb2ac3e77fd50a338e114adae6695fcb701a22c1cd9 | 1254 -> 760 px |

Fonts in assets/fonts are unmodified copies of the app target's `Resources/Fonts` files (see assets/fonts/OFL.txt).
