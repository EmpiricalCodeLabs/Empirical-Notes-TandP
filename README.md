# Empirical-Notes-TandP

Terms and Conditions and Privacy Policy for the Empirical Notes app, published with GitHub Pages:
https://empiricalcodelabs.github.io/Empirical-Notes-TandP/

The Google Play privacy policy link and data deletion link point to
https://empiricalcodelabs.github.io/Empirical-Notes-TandP/privacy-policy.html

## Editing

- `privacy-policy.html` and `terms-of-service.html` are **generated**. Don't edit them here.
  The text comes from `assets/terms_privacy/en/privacy.json` and `terms.json` in the (private) app repo,
  which the app shows in-app. After changing the JSON, run `python tool/generate_legal_pages.py`
  in the app repo. It writes both pages into this clone (default location: `../Empirical-Notes-TandP`
  next to the app folder). Then commit and push here.
- `index.html` and `app_icon.png` are maintained here by hand.
