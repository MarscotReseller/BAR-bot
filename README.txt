════════════════════════════════════════
  SHOP TELEGRAM BOT — SETUP GUIDE
════════════════════════════════════════

REQUIREMENTS
────────────
• Python 3.11 or higher
• pip

INSTALL
────────────
pip install -r requirements.txt

CONFIGURE
────────────
Open bot.py and edit the CONFIG section at the top:

  BOT_TOKEN        — your bot token from @BotFather
  ADMIN_IDS        — list of admin Telegram user IDs (e.g. [123456789, 987654321])
  VERIFY_CHANNEL   — your channel ID (negative number) that users must join
  SUPPORT_CONTACTS — your support usernames
  BINANCE_ID       — your Binance Pay ID

Optional QR images (place in same folder as bot.py):
  UPI QR:     upi_qr.jpg  or  qr.jpg
  Binance QR: binance_qr.jpg  or  binance.jpg

RUN
────────────
python3 bot.py

HOW FILE MANAGEMENT WORKS
────────────────────────────
Admin adds a file:
  1. Open Admin Panel → tap "📁 Add File"
  2. Select category → select product
  3. Send the IPA/APK link as a text message
     OR send the file directly as a document

When a buyer is approved:
  • The key is sent automatically
  • The file/link is also sent automatically
  • No manual steps needed

Admin removes a file:
  1. Open Admin Panel → tap "🗑️ Remove File"
  2. Select category → select product
  3. Choose "Remove Next File" or "Clear ALL Files"

NOTE: Files are stored per product (not per duration).
      One file in stock covers all durations (1 Day, 7 Days, 31 Days, etc.)

DATA
────────────
All data is saved to bot_data.json in the same folder.
Back this file up regularly — it contains all keys, files, and user data.

════════════════════════════════════════
