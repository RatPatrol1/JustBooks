# JustBooks

Bookkeeping for small businesses, on your own Windows PC. Free, with no subscription and no account to sign up
for. Your books stay on your computer.

**Downloads are on the [Releases](../../releases) page.** This repository holds only the installers and their
license; the program's source code isn't published.

> **Early development builds.** The first releases are development versions (marked "Pre-release"). Expect rough
> edges, and keep your own backups.

## What it does

- **Books:** businesses, a chart of accounts, expenses, deposits, transfers, checks, journal entries, closing a
  period.
- **Bank and card statements:** import CSV, OFX, QFX or QBO files, match them, learn rules, reconcile.
- **Sales:** customers, items, quotes and estimates, invoices, payments, deposits, credit memos, statements, sales
  tax; PDFs to print or email.
- **Purchases:** vendors, bills to pay, 1099 tracking.
- **Receipts:** drop in PDFs and photos, or email them in. They're read and attached to the matching bank or card
  charge. Turn a sideways photo or scan the right way up on the receipt's page.
- **Phone app (Android):** take a photo of a receipt and it goes straight to your PC, over your home Wi-Fi or (with
  Tailscale) from anywhere. No cloud service in between.
- **Projects and jobs**, **assets**, and **reports:** profit and loss, balance sheet, cash flow, budget vs actual,
  Schedule C, a year-end package for your accountant, Excel export.
- **Backups** to OneDrive, a NAS or a USB drive, encrypted if you want.
- **US federal tax lines** (Schedule C) built in; Minnesota rules and forms for Minnesota businesses.

## Installing

1. Download `JustBooks-Setup-<version>.exe` from [Releases](../../releases) and run it. No admin rights needed: it
   installs for your Windows user only.
2. **Windows may say "Windows protected your PC".** The installer isn't code-signed yet, so Windows doesn't know
   the publisher. Click **More info**, then **Run anyway**. You'll only see this when installing from a download.
3. Pick where your books are kept. Use a folder on this PC's own drive, not OneDrive or a network drive (backups go
   there instead).

Updates are offered inside the program (Settings, Updates). Each one is signed and checked before it installs, and
your books are backed up first. Nothing installs without your click.

## The phone app (Android)

The phone app isn't on Google Play. It's attached to each release as `JustBooks-Phone.apk` and installed from that
file ("sideloading"). It only talks to JustBooks on your own PC.

1. On the PC, open JustBooks and go to **Phone link**. Click **Turn on**.
2. Under **Get the phone app**, point the phone's camera at the QR code and tap the link (or type the address shown
   into the phone's browser). The phone downloads `JustBooks-Phone.apk`.
   - No download on the phone? Download the APK from [Releases](../../releases) on the PC and copy it to the phone's
     Download folder with a USB cable or a cloud drive.
3. Open the APK from the download notice or the phone's **Files** app. The first time, Android says installing apps
   from this source isn't allowed: tap **Settings**, turn on **Allow from this source**, go back and tap
   **Install**. (You can turn that permission off again afterward.)
4. If Google Play Protect says it doesn't recognize the developer, that's because the app isn't from Google Play:
   tap **More details**, then **Install anyway**.
5. Open the app and tap **Pair with PC**. On the PC, click **Pair a phone** and type the 8-digit code into the phone.
   The phone and PC need to be on the same Wi-Fi to pair.

**Updates:** when a release has a newer phone app, install it the same way. It installs over the old one and keeps
the pairing and any photos still waiting to send. Don't uninstall first: that removes them.

**Check a download** (optional): each release's `SHA256SUMS.txt` lists the SHA-256 of every file, the APK included.

## License and warranty

Free to use for personal or business use under the [Freeware License](LICENSE). Each release includes the
licenses of the third-party parts it uses.

**No warranty.** JustBooks is provided "as is", without warranty of any kind, express or implied. You use it at
your own risk and are responsible for checking your own records and keeping your own backups.
