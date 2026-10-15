# 💰 Duit Ledger

**Spend with clarity. Pay down debt. Save for what matters.**\
Your finances stay private, right on your device.

Duit Ledger is a simple, free and private money tracker. Record your
income and spending, understand where your money goes, and plan how to
clear debt and reach your savings goals.

**[Open Duit Ledger](https://t2rt2re.github.io/duit-ledger/)**

Available in English, Bahasa Melayu, 中文 and தமிழ் (Tamil is partly
translated). Includes light and dark mode, four colour themes, and a
warm, minimalist interface.

## Features

### Monthly ledger

-   Record money in (salary, bonus) and money out (spending), with quick
    category picks and emoji for each category.
-   Edit, delete and search entries.
-   See your leftover money, a spending pie chart and a six-month trend.
-   Check your daily spending allowance for the rest of the month,
    monthly review, comparison with last month and logging streak.
-   Set monthly limits per category and get a warning when you go over.
-   Save recurring bills (rent, internet, subscriptions) and add them to
    any month in one tap, with reminders when a bill is due soon.
-   Use the 50/30/20 guide based on your income.

### Debt planner

-   Add debts with balances, yearly interest rates and minimum payments,
    then estimate your debt-free date and total interest.
-   Compare **avalanche** (highest interest first, usually saving more
    interest) and **snowball** (smallest balance first, for quicker
    wins) strategies.
-   Record payments and track your progress with a "% paid" bar. Each
    payment is also added to your ledger.
-   Use quick-start buttons for common Malaysian debts. The rates are
    typical estimates, so update them to match your own loan or
    statement.

### Savings and net worth

-   Create multiple savings goals, such as Raya, a holiday or an
    emergency fund, with an optional target month and suggested monthly
    amount.
-   See an emergency fund target based on your average spending.
-   Track net worth using your assets, savings goals and debts.
-   Try the no-spend challenge by avoiding a category for a chosen
    number of days.
-   Track a Wedding Fund and identify which partner recorded a
    transaction.

### Tax relief tracker

-   Track spending against common LHDN tax relief limits.
-   The listed limits are for YA2025. Check LHDN for the limits that
    apply to your assessment year.

### Tools

-   Download a formatted monthly report, including CSV export and
    print/PDF options.
-   Share a summary image that shows percentages only, without ringgit
    amounts.
-   Import a bank statement CSV. Check income and spending types after
    importing because bank formats differ.
-   Save and restore a backup file, and export entries.
-   Split a bill between friends.
-   Enable an optional PIN lock.
-   Install it on your phone and use it offline.

## Auto-save and data storage

Duit Ledger saves changes automatically in your browser, so your entries
and settings should still be there when you close and reopen the app in
the **same browser on the same device**. You do not need to press a save
button for every change.

Your data is stored locally in your browser. It is not automatically
synchronised between different devices or browsers. If you clear your
browser data, use a different browser, or uninstall/reset the app, your
data may be lost. **Use "Save backup" regularly** and keep the backup
somewhere safe.

If you use the app on more than one device, restore a backup on the
other device when needed. Changes made on one device will not
automatically appear on the other.

## How to use

1.  Open the [Duit Ledger
    website](https://t2rt2re.github.io/duit-ledger/).
2.  In **Monthly ledger**, add your salary or other income first, then
    record your spending.
3.  In **Debt planner**, add each debt and the extra amount you may be
    able to pay each month.
4.  In **Savings goals**, create goals and add your assets.
5.  Use **Save backup** regularly to keep a copy of your data.

### Install on your phone

-   **Android (Chrome):** Open the site, tap the menu (⋮), then choose
    **Install app** if available.
-   **iPhone (Safari):** Tap **Share**, then **Add to Home Screen**.

Before installing, save a backup. The installed app may not share data
with the browser version, so open the installed app and use **Restore
backup** if needed.

## Privacy

Your financial data is stored in your browser's local storage. The app
does not require an account, send your entries to a server, or use
analytics. The project does not sell or share your financial data.

A few technical details: - The page loads the Nunito font from Google
Fonts, so your browser contacts Google when the page opens. Your
financial entries are not included in that request. - A service worker
caches the app files so it can work offline after the app has been
loaded. - The optional PIN lock helps keep casual viewers out, but it
does **not** encrypt your data. If you forget your PIN, you may need to
clear this site's browser data and restore a backup.

## Project files

  File                             Purpose
  -------------------------------- -------------------------------------------
  `index.html`                     The app's HTML, CSS and JavaScript
  `manifest.json`                  Enables installation on supported devices
  `sw.js`                          Offline support
  `icon-192.png`, `icon-512.png`   App icons

## Run it yourself

No build step is required. Download the project files, keep them in the
same folder, and open `index.html` in a browser.

For installation and offline support, serve the files over HTTPS, for
example with GitHub Pages.

### Host it on GitHub Pages

1.  Open your repository's **Settings**.
2.  Select **Pages**.
3.  Under the build and deployment settings, choose **Deploy from a
    branch**.
4.  Select the `main` branch and `/ (root)` folder, then save.

## Built with

Plain HTML, CSS and JavaScript. No frameworks. The app loads the Nunito
font from Google Fonts.

## Disclaimer

Duit Ledger is a budgeting aid, not financial, tax or legal advice. Debt
payoff estimates are simplified and may differ from the amounts charged
by your lender. Tax relief limits can change, so confirm the applicable
limits with LHDN. Check imported bank data and quick-start interest
rates against your own statements.

## License

Released under the [MIT License](LICENSE). © 2026 t2rt2re
