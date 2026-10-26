# ☕ Coffee Counter

A tiny phone app that tracks how many home-made coffees it takes for your coffee machine to pay for itself.

- **+1 Coffee** each time you make one (−1 to undo)
- **Log a purchase** for beans, milk or anything else; it's added to your total cost. Beans take a bag size (125 g, 250 g, 300 g, 500 g, 1 kg or any other amount) and show the price per kg
- **One-tap Add coffee button** on your home screen (see below)
- **Settings**: machine price, how much each coffee saves you (e.g. café price), currency (Euro by default) and a manual coffee count. Amounts always show as €1,234.50. Prices can be typed as 4.50 or 4,50
- Export/import a JSON backup

Break-even = (machine price + purchases) ÷ saved per coffee.

Everything is stored on your phone (localStorage). No account, no server.

## Put it on your phone

1. In the GitHub repo go to **Settings → Pages**, set the source to **Deploy from a branch**, then pick this branch and `/ (root)`.
2. Open the Pages URL on your phone.
3. **iPhone (Safari):** Share → *Add to Home Screen*. **Android (Chrome):** ⋮ → *Add to Home screen* / *Install app*.

Once installed it opens full-screen and works offline.

## One-tap "Add coffee" button (Android)

After installing the app:

1. Long-press the Coffee Counter icon on your home screen. An **Add coffee** shortcut pops up.
2. Drag that shortcut to an empty spot on your home screen to pin it.
3. Tapping it adds one coffee straight away and shows how many are left to go.

This is an app shortcut, not a true home-screen widget: tapping it briefly opens the app.
