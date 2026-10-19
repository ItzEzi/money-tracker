# OfferDesk source

OfferDesk is served from `../offerdesk.html`. Edit the files here, then run:

    python3 offerdesk-src/build.py

That rebuilds `offerdesk.html` and bumps `offerdesk-version.json`. After you push, every open copy refreshes itself on its next load.

- `styles.css`, `js/*.js` (concatenated in name order), `bridge.gs` (the Google Apps Script bridge, embedded in the page for the Connect screen)
- `SCREEN-MAP.md`: what each SendOffers screen has and where it lives in OfferDesk
