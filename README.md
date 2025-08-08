Local Subscription Finder
This is a simple offline tool that helps you find recurring payments in your bank statements — without sending your data anywhere.

How it works
Export your transactions from your bank (or use the included fake_transactions.csv for testing).

Open subscription_finder.html in your web browser.

Click Upload CSV and select your file.

The tool will scan your transactions for payments that:

Have the same merchant name

Have the same amount

Happen at regular intervals (weekly, monthly, yearly)

All processing happens entirely in your browser, so your data never leaves your computer.

File format
The CSV should have three columns:

python-repl
Copy
Edit
Date,Merchant,Amount
2025-01-03,Netflix,15.99
2025-02-03,Netflix,15.99
...
Date — in YYYY-MM-DD format

Merchant — the payee name (e.g., "Netflix")

Amount — numeric amount without currency symbols

Testing
If you don’t have a bank CSV handy, use the provided fake_transactions.csv to try it out. It contains a mix of recurring subscriptions and one-off purchases.

Why this is safe
No servers

No sign-ups

No internet required
You can even disconnect your Wi-Fi and it will still work.
