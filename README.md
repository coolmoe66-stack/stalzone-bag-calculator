# STALZONE Lost Bag Calculator

A lightweight, unofficial browser-based calculator for estimating the value of STALZONE lost bags.

## What it does

- Enter a barter material and quantity.
- Converts the quantity into its 20-stack block/bundle equivalent.
- Uses the saved block price to estimate the bag's value.
- Saves block price edits locally in the user's browser.
- Works entirely client-side with no login, database, or backend.

## GitHub Pages deployment

1. Create a new GitHub repository, for example `stalzone-bag-calculator`.
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`.
6. Save. GitHub will provide the public URL once Pages is enabled.

## Updating prices

Open **Block prices / settings** in the calculator and change the price for any bundle. The values are stored only in that browser.

To change the default prices for every new visitor, edit the `defaults` object in `index.html`.

## Files

- `index.html` — complete calculator
- `favicon.svg` — site icon
- `site.webmanifest` — basic installable-site metadata

## Disclaimer

This is an unofficial fan-made tool and is not affiliated with EXBO.
