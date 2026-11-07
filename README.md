# Riven Scoper

**Is this riven worth rolling, and what is it worth?** Riven Scoper is an Android app for Warframe players. It reads live riven listings from [warframe.market](https://warframe.market) and real in-game trade data from Digital Extremes. It tells you which weapons are worth rolling, what the god roll is, and whether an asking price is fair.

> Riven Scoper is a free fan project. It is not affiliated with Digital Extremes or warframe.market.

### 🌐 No Android phone? Use the website: **[rivenscoper.com](https://rivenscoper.com)**

The website is the same app, with nothing to install. It works on iPhone, iPad, PC and Mac, and has everything the app has: weapon checks, the Analyzer, Pulse, your collection, warframe.market sign-in, listing and Messages. On a phone, use your browser's **Add to Home Screen** to open it like an app.

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

You can also check for updates yourself under **☰ → Dev tools → Version and updates**.

## Signing in (optional)

When you first open the app, you can sign in with your warframe.market account or **Continue without signing in**.

- **Without signing in** you can use everything except posting listings, messages and collection sync.
- **Signing in** lets you list your rivens for sale and answer warframe.market messages from the app.
- Your password goes only to warframe.market and is never saved. The app keeps only the sign-in token warframe.market gives back, in your phone's secure storage.
- **On the website,** your password passes securely through rivenscoper.com to warframe.market and is never stored. The sign-in token is kept in a secure cookie that only rivenscoper.com can use.
- Sign in or out any time from the **☰** menu.

### Your collection follows you

When you're signed in, your Collection and saved Analyzer rivens are kept with your warframe.market account, so they're there on the app, on the website and on any new phone.

- The synced copy is stored encrypted, and only your signed-in account can read it back.
- Changes made on two devices are combined.
- Turn sync off, or delete the synced copy, under **☰ → Dev tools → Back up and restore**.

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

With an asking price, you get a verdict: **STEAL**, **UNDERPRICED**, **FAIR**, **ELEVATED** or **OVERPRICED**. You also see similar listings, so you can compare.

### Pulse: what the market is doing

- **Market board:** weapons ranked over 24 hours, 7 days or 30 days, by most listings, top gainers, top losers, most expensive or cheapest.
- **Popular weapons:** recent listings for the 15 weapons whose rivens DE recorded the most in-game trades for last week, newest first, with each weapon's demand score.
- **Most recent listings:** the newest rivens posted on warframe.market. This refreshes every minute while you are looking at it.

### Collection: your rivens

- Browse every weapon that can have a riven. Tick the weapons you own, star your favorites, and use the filters to narrow the list.
- Tap **Add riven** to save a riven you have: its stats, values and reroll count. Each saved riven gets its own price check.
- **Selling, when signed in:**
  - **List:** set a price, preview the listing, then post it to warframe.market.
  - **Change price:** update the price of a riven you've listed.
  - **Sold:** mark it sold and record what it sold for.
  - **Remove:** take the listing down. Tap twice to confirm.

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
- **App**
  - **Dev tools:**
    - your version, and a button to check for updates;
    - **Back up and restore**, which copies your collection and settings as text you can save and restore later, plus the **Collection sync** settings.
  - **Acknowledgements:** credits for the data sources and open-source tools the app uses.
  - **Changelog:** what changed in each update.

The Android back button steps back through the app: it closes the menu, leaves an open chat, and returns to the Weapon tab before it closes the app.

---

## Good to know

- **Prices are asking prices.** warframe.market listings show what sellers want, not what they got. The app removes stale and bait listings and leans on cautious estimates, but treat prices as a guide.
- **PC data.** Prices, trade demand and World State are for the PC platform.
- **Be patient with the market check.** warframe.market limits how often apps can search, so the app paces its requests to stay a good neighbour.

## Troubleshooting

| Problem | Fix |
|---|---|
| **"App not installed"** when updating | Your installed copy was signed differently, which can happen with very early builds. Back up in ☰ → Dev tools, uninstall, install the latest release, then restore. You only need to do this once. |
| **"Harmful app blocked"** from Play Protect | Tap **Install anyway**. It's a general warning for apps outside the Play Store. |
| **"Sign-in expired"** | Sign in again from the ☰ menu. |
| **The god roll list keeps saying "Quick estimate"** | The live check takes about a minute. If it stops with an error, wait a few minutes or tap **Recheck**. |
| **No listings for a weapon** | warframe.market may be busy. Tap the refresh button next to the search box. |
| **My collection isn't on my other device** | Sign in to the same warframe.market account on both, then tap **Sync now** under ☰ → Dev tools → Back up and restore. |

## Credits

Data from [warframe.market](https://warframe.market), and Digital Extremes' public world state and weekly riven trade data. Node and mission names come from WFCD's open-source data. The app is built with Capacitor. The full list is in the app under **☰ → Acknowledgements**.
