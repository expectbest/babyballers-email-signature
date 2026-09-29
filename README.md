# BabyBallers email signature pictures

These are the pictures in every BabyBallers email signature, made by the portal at
<https://app.babyballers.com/email/signature>.

They are served by jsDelivr from this repository, pinned to the `v1` tag:

```
https://cdn.jsdelivr.net/gh/expectbest/babyballers-email-signature@v1/<file>
```

for example <https://cdn.jsdelivr.net/gh/expectbest/babyballers-email-signature@v1/logo.png>.

**Never rename, move or delete a file or the `v1` tag.** Signatures already in people's inboxes
point at them, and a signature is pasted once and kept for years. A changed picture goes in as a
new tag (`v2`), never over `v1`, and the portal is then pointed at the new tag.

| File | What it is | Size |
|---|---|---|
| `logo.png` | The BabyBallers logo, top left | 492 x 273 |
| `banner-learn-through-play.png` | The #LearnThroughPlay banner along the bottom | 1462 x 262 |
| `social-facebook.png` | Facebook icon | 55 x 55 |
| `social-instagram.png` | Instagram icon | 55 x 55 |
| `social-tiktok.png` | TikTok icon | 55 x 55 |
| `social-youtube.png` | YouTube icon | 55 x 55 |
| `social-whatsapp.png` | WhatsApp icon | 55 x 55 |
| `button-whatsapp-us.png` | The "WhatsApp us" button | 461 x 89 |
| `button-book.png` | The "Book your class" button | 461 x 89 |
| `button-find-us.png` | The "Find us" button | 461 x 89 |

Why here: the pictures used to load from a website behind SiteGround's anti-bot, which sometimes
answers a picture request with a challenge page instead, so signatures showed broken images.
jsDelivr serves them to anyone, email apps included, with nothing in the way.
