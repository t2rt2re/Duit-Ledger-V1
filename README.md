# 💰 Duit Ledger

**Spend with clarity. Pay down debt. Save for what matters.**  
Your finances stay private, right on your device.

Duit Ledger is a simple personal money tracker that helps you record income and spending, plan debt repayments, set savings goals and keep an eye on your finances.

**[Open Duit Ledger](https://github.com/t2rt2re/Duit-Ledger-V1)**

Available in **English and Bahasa Malaysia**, with light and dark mode.

## Features

### 📒 Monthly ledger
- Record money in, such as salary or bonus, and money out, such as everyday spending.
- Add a category, emoji, date, amount, account and optional note to an entry.
- View entries for the current month or all months.
- View spending charts and a six-month trend.
- Set your month around the calendar, a fixed day, or when your salary arrives.
- Carry leftover money into the next month if you choose.

### 🧾 Bills, limits and reports
- Save recurring bills and add them to the selected month.
- Set monthly spending limits by category.
- Create your own categories and choose an emoji.
- View a yearly summary.
- Download a monthly report or share a summary image.
- Import bank transactions from a CSV file. Check the imported transaction types and details after importing.

### 💳 Debt planner
- Add debts with the balance, annual interest rate and minimum monthly payment.
- Compare **avalanche** repayment (highest interest first) with **snowball** repayment (smallest balance first).
- Set an extra amount you can pay each month and review your repayment plan.
- Use the quick-start debt options as a starting point, then adjust the rates and details to match your own statements.

### 🌱 Savings goals and spending tools
- Create a savings goal with a target amount and optional target month.
- Set up a no-spend challenge for a chosen category and number of days.
- Add accounts or wallets and record assets to help track your overall financial position.
- Estimate an emergency fund target based on your spending.

### 💍 Tabung Kahwin
- Set a wedding date and savings target.
- Add deposits and withdrawals to track the fund.
- Set names for yourself and your partner, and choose who recorded each transaction.
- Plan wedding expenses and track estimated and paid amounts.

### 🧾 Tax relief tracker
- Track expenses against the tax relief categories shown in the app.
- The app notes that its displayed limits follow **YA2025** and may differ for YA2026. Check the latest LHDN guidance before filing your taxes.

### 🍽️ Split a bill
- Split a bill equally or enter individual amounts for a custom split.
- Include service charge or tax and copy the breakdown.

### ⚙️ Backup and PIN
- Save a backup file containing your ledger, debts, savings, accounts, wedding fund and tax tracker.
- Restore your data from a backup file.
- Set an optional PIN lock.

## Automatic saving and your data

Your changes are saved automatically on the device and in the browser you use. When you close and reopen Duit Ledger in the same browser on the same device, your saved data should still be available.

Your data is **not automatically synchronised between devices or browsers**. Clearing browser/site data, resetting the browser or using a different device may remove or make your data unavailable. Use **Save backup** regularly and keep the backup file somewhere safe.

## How to use

1. Open [Duit Ledger](https://t2rt2re.github.io/duit-ledger/).
2. In **Monthly ledger**, add your salary or other income, then record your spending.
3. Use **Bills & limits** to add recurring bills and set spending limits.
4. In **Debt planner**, enter your debts and repayment details.
5. Create savings goals and add accounts or assets if needed.
6. Use **Tabung Kahwin** to track wedding savings and planned expenses.
7. Open **Backup** from the settings (⚙️) area and select **Save backup** regularly.

## Install on your phone

- **Android (Chrome):** Open the website, tap the menu (⋮), and choose **Install app** if the option is available.
- **iPhone (Safari):** Open the website, tap **Share**, then **Add to Home Screen**.

Keep a backup before installing or changing browsers. If the installed app does not show your existing data, use **Restore backup**.

## Privacy

Duit Ledger stores your entries in your browser on your device. It does not require an account, and the app's financial records are not designed to sync to a server. The app footer warns that clearing browser data can erase saved information.

The app loads the Nunito font from Google Fonts, which means your browser may contact Google to load the font. The optional PIN lock is intended to deter casual access; it does **not** encrypt your financial data. Keep your device secure and save backups regularly.

## Run it yourself

The app is a standalone HTML file. Download the HTML file and open it in a browser.

For a public website or installation/offline use, host the app over HTTPS, for example with GitHub Pages.

### Host on GitHub Pages

1. Upload the app file to your GitHub repository.
2. If you want it to open as the repository homepage, name the file `index.html`.
3. Open **Settings → Pages**.
4. Under the deployment settings, select **Deploy from a branch**, choose the `main` branch and `/ (root)`, then save.

## Built with

HTML, CSS and JavaScript.

## Disclaimer

Duit Ledger is a budgeting tool, not financial, tax or legal advice. Debt repayment estimates are simplified and may differ from the amount charged by a lender. Interest rates and imported bank data should be checked against your own statements. Tax relief limits can change, so confirm the relevant limits with LHDN.

## Credits

Made with ♡ by Aisha Jong.
"""

output_path = "/mnt/data/README.md"
pypandoc.convert_text(readme, "md", format="md", outputfile=output_path, extra_args=["--standalone"])
print(f"README dikemas kini berdasarkan fungsi yang terdapat dalam fail aplikasi: {output_path}")
