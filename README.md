# Riven Scoper

**Is this riven worth rolling, and what is it worth?** Riven Scoper is an Android app for Warframe players. It reads live riven listings from [warframe.market](https://warframe.market) and real in-game trade data from Digital Extremes. It tells you which weapons are worth rolling, what the god roll is, and whether an asking price is fair.

> Riven Scoper is a free fan project. It is not affiliated with Digital Extremes or warframe.market.

### 🌐 No Android phone? Use the website: **[rivenscoper.com](https://rivenscoper.com)**

The website is the same app, with nothing to install. It works on iPhone, iPad, PC and Mac, and has everything the app has: weapon checks, the Analyzer, Trends, your collection, warframe.market sign-in, listing and Messages. On a PC or a tablet in landscape, long pages use two columns. On a phone, use your browser's **Add to Home Screen** to open it like an app.

---

## Install the Android app

1. On your Android phone, open the **[latest release](https://github.com/pointlessgame47-prog/riven-scoper-releases/releases/latest)**.
2. Under **Assets**, tap the `.apk` file to download it.
3. Open the downloaded file. If Android asks, allow your browser to install apps.
4. If **Google Play Protect** says the app may be harmful, tap **Install anyway**. Play Protect warns about most apps that don't come from the Play Store.

## Updates

You only install by hand once. After that, the app updates itself:

- When a new version is out, a banner at the top says **Update available**.
- Tap **Update now**. The update downloads inside the app, then Android asks you to confirm the install.
- The first time, Android asks you to turn on **Allow from this source** for Riven Scoper. Turn it on and come back to the app.
- Your collection and settings stay after updating.

You can also check for updates yourself under **☰ → Changelog**, which shows your version and a **Check for updates** button.

## Signing in (optional)

When you first open the app, you can sign in with your warframe.market account or **Continue without signing in**.

- **Without signing in** you can use everything except saving your Collection to your account, posting listings, importing your listings and messages.
- **Signing in** saves your Collection to your account so it's on every device, lets you import your warframe.market riven listings, list rivens for sale and answer warframe.market messages.
- Your password goes only to warframe.market and is never saved. The app keeps only the sign-in token warframe.market gives back, in your phone's secure storage.
- **On the website,** your password passes securely through rivenscoper.com to warframe.market and is never stored. The sign-in token is kept in a secure cookie that only rivenscoper.com can use.
- **Saving your Collection:** to know which account to save under, the app or website shows rivenscoper.com your sign-in token, and rivenscoper.com asks warframe.market which account it belongs to. The token is never stored.
- Sign in or out any time from the **☰** menu.
- **Your warframe.market status:** when you're signed in, the top of the **☰** menu shows your account and status. Set **Online**, **Online in game** or **Invisible**, so buyers know whether to message you. Choose how long to keep it (30 minutes to 4 hours) and you'll switch to Invisible after that, or keep it while the app is open. warframe.market only shows you as online while Riven Scoper, its site or its app is open. It also links to your warframe.market settings, and Sign out is just below.

---

## The tabs

### Weapon: is it worth rolling?

Type a weapon name and Riven Scoper looks at its current riven listings.

- **The verdict** at the top: **Worth rolling**, **Promising**, **Maybe**, **Skip it** or **Not worth rolling**, with a short explanation.
  - **Real demand check:** the verdict also uses DE's weekly in-game trade data. If a weapon has plenty of high listings but almost nobody actually buys its rivens, the app says **Not worth rolling** and explains why.
- **Real trade demand:** a small chart of how often the weapon's rolled rivens were traded in game over the last six weeks. 100 means the most-traded riven type that week.
- **Listings summary:** how many listings there are, how many sellers are online, and the low, median and high prices.
- **God roll and sell price:** the best stat combinations, the best negative to have, and a likely sale price.
  - The app first shows a quick estimate. It then checks the live market for the top combinations, which takes about a minute, and shows the time remaining.
  - Results are kept for 6 hours. Tap **Recheck** to run it again.
- **Rolls and Kuva:** your odds of hitting the god roll on each reroll, and roughly how much Kuva it takes.
- **What each stat adds to the price:** which stats push the price up, and which negatives hurt it.

**Tip:** the **Only listings made after the Disposition removal** checkbox hides old listings priced before the change. Leave it on for current prices.

### Analyzer: price-check one riven

Check what a specific riven is worth, or whether someone's asking price is fair.

1. Pick the weapon and its 2 or 3 positive stats.
2. Optionally add the negative stat, the reroll count and the asking price.
3. Tap **Analyze riven**.

You can also paste a warframe.market listing link and tap **Load listing**.

With an asking price, you get a verdict: **STEAL**, **UNDERPRICED**, **FAIR**, **ELEVATED** or **OVERPRICED**. You also see similar listings, so you can compare. Tap **WFM ↗** on one to see it on warframe.market.

### Trends: what the market is doing

- **Rankings:** weapons ranked over 24 hours, 7 days or 30 days, by most listings, top gainers, top losers, most expensive or cheapest. Gainers and losers compare listings posted in that period with the period before, so the 7-day and 30-day changes appear once Riven Scoper has watched the market long enough, and the tab shows the date they start.
- **Popular weapons:** recent listings for the 15 weapons whose rivens DE recorded the most in-game trades for last week, with each weapon's demand score. The menu at the top right sorts them by newest, price or demand.
- **Most recent listings:** the newest rivens posted on warframe.market. This refreshes every minute while you are looking at it. Tick **Popular weapons only** to see just those 15 weapons.
- Each listing in Popular weapons and Most recent listings has a **WFM ↗** button that opens it on warframe.market, and an **Analyze weapon** link that checks that weapon here.

### Collection: your rivens

- **Saved to your account:** while you're signed in, your Collection (owned weapons, every riven you've added or saved, favorites and listing records) and the rivens you save in the Analyzer are saved to your warframe.market account on the Riven Scoper server, encrypted. Sign in on another phone or on the website and it's all there. If you change things on two devices, both changes are kept. **Your account → How saving and importing work** lets you turn saving off for a device or delete the saved copy.
- Browse every weapon that can have a riven. Tick the weapons you own, star your favorites, and use the filters to narrow the list.
- **Live on WFM** lists every riven you have listed on warframe.market right now, each with a **WFM ↗** button. Every riven shows where it stands: **Live** with its price and a gold edge, **Hidden** (listed but hidden from buyers), **In app only**, **Sold** or **Listing closed**. Deleting a riven that's still listed takes the listing down too: tap **Delete**, then tap again to remove the listing and delete. Weapons show how many of their rivens are live, and **Filter → Listed on WFM** narrows the list to them.
- **Import from warframe.market**, at the top, brings in the rivens you have listed on warframe.market when you're signed in. Their weapons are marked as owned, and each riven is added with its stats, name, rerolls, rank, mastery, polarity, price and listing, ready to reprice or mark sold. It runs when you open the tab, and **Import my listings now** runs it again. Rivens you've sold or taken down on warframe.market are marked as removed.
- Tap **Add riven** to save a riven you have: its stats, values and reroll count. You don't need to type its name: pick the stats and the app lists every name they can make, most likely first, or choose **Other** to type it. Each saved riven gets its own price check.
- **Selling, when signed in:**
  - **List:** set a price, preview the listing, then post it to warframe.market.
  - **Change price:** update the price of a riven you've listed.
  - **Sold:** mark it sold and record what it sold for.
  - **Remove:** take the listing down and keep the riven. Tap twice to confirm.
  - **Delete:** remove the riven from your Collection. If it's still listed, this takes the listing down too.

### Messages: warframe.market chat

When you're signed in, this tab shows your warframe.market conversations.

- Read and reply to messages. New messages arrive live while the app is open.
- A badge on the tab shows unread messages. A pop-up appears when someone messages you while you're on another tab; tap it to open the chat.
- **Leave** removes a conversation. Tap twice to confirm.
- You can't start new conversations here yet. Start them on warframe.market and they'll show up in the app.
- Messages only arrive while the app is open. There are no phone notifications yet.

---

## The ☰ menu

- **Sign in / Sign out** to warframe.market.
- **Miscellaneous tools**
  - **World State:** what's happening in Warframe right now (PC):
    - day/night and other cycles for Cetus, Orb Vallis, Cambion Drift and Duviri;
    - today's Sortie and this week's Archon Hunt;
    - Void Fissures by relic tier, with Steel Path and Void Storm tabs;
    - when Baro Ki'Teer arrives, and what he's selling;
    - Nightwave acts and any running events.

    It refreshes every minute while the page is open.
  - **Riven guide:** everything about rivens in one place: getting and unveiling them, reading one, how names work, rolling and Kuva costs, trait locking, splicing, the end of Disposition, good stats and harmless negatives, status and elements, common myths, pricing, trading and transmuting.
- **App**
  - **Changelog:** what changed in each update, plus your version and a button to check for updates in the app.
  - **Our process:** exactly where Riven Scoper's data comes from and how every price, score and verdict is worked out.
  - **Acknowledgements:** credits for the data sources and open-source tools the app uses, and how visits are counted anonymously.
  - **Dev tools:** tools for the Riven Scoper team, including Back up and restore. They need the team's dev tools password.

The Android back button steps back through the app: it closes the menu, leaves an open chat, and returns to the Weapon tab before it closes the app.

---

## Good to know

- **Prices are asking prices.** warframe.market listings show what sellers want, not what they got. The app removes stale and bait listings and leans on cautious estimates, but treat prices as a guide.
- **PC data.** Prices, trade demand and World State are for the PC platform.
- **Be patient with the market check.** warframe.market limits how often apps can search, so the app paces its requests to stay a good neighbour.

## Troubleshooting

| Problem | Fix |
|---|---|
| **"App not installed"** when updating | Your installed copy was signed differently, which can happen with very early builds. Uninstall, then install the latest release. You only need to do this once. Sign in again and your saved Collection loads from your account. |
| **"Harmful app blocked"** from Play Protect | Tap **Install anyway**. It's a general warning for apps outside the Play Store. |
| **"Sign-in expired"** | Sign in again from the ☰ menu. |
| **The god roll list keeps saying "Quick estimate"** | The live check takes about a minute. If it stops with an error, wait a few minutes or tap **Recheck**. |
| **No listings for a weapon** | warframe.market may be busy. Tap the refresh button next to the search box. |
| **My rivens aren't in my collection on another device** | Sign in to the same warframe.market account on both, and check **Collection → Your account** says it's saved. Tap **Sync now** to load the latest. |

## Credits

Data from [warframe.market](https://warframe.market), and Digital Extremes' public world state and weekly riven trade data. Node and mission names come from WFCD's open-source data. The app is built with Capacitor. The full list is in the app under **☰ → Acknowledgements**.
