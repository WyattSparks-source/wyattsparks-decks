# wyattsparks-decks

decks.wyattsparks.com. Shareable HTML decks at unlisted slugs. Separate from wyattsparks.com;
the two share nothing but the domain.

Slug convention: `/<client-or-project>-<topic>-<YYYY-MM>/index.html`

Publishing: push to `main` is the deploy. Netlify publishes this whole repo within seconds.
Retiring: delete the deck's folder and push. Git history keeps the file; nothing is ever lost.

Every page carries `noindex, nofollow` in a meta tag and an `X-Robots-Tag` header. A deck is
reachable only by someone who has the link. Keep that meta tag in every deck's index.html.
