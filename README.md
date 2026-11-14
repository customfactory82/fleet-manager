FLEET MANAGER - on-phone app (Custom Factory)

WHAT THIS IS
A web app for companies that run their own vehicles and drivers.
Vehicles, renewals, drivers, trip schedule (sent to drivers by WhatsApp or SMS),
trip log, fuel log, pre-trip checks, service, repairs, damage, tyres and monthly costs.
Every record and photo is saved on the phone that uses it. No sign-in needed.
It works without internet once it has been opened.

WHAT'S IN THIS FOLDER
index.html             the app
manifest.webmanifest   lets phones install it like an app
sw.js                  makes it work offline
icons/                 app icons
fonts/                 Barlow fonts (open licence, see fonts/OFL-LICENSE.txt)

ACTIVATION
The app asks for a company name and an activation code the first time it opens.
Each code only works with the company name it was made for, and the name is then
locked in the app. Make codes on your private "Fleet Logbook Activation Codes" page
in Claude, with "Fleet Manager" selected (never put that page or its key here).

GIVE IT TO A CUSTOMER
Make their activation code, then send them the message from the codes page.
They install it on the office phone or tablet:
  iPhone:  Safari > Share > Add to Home Screen  (always open it from the Home Screen)
  Android: Chrome > menu (3 dots) > Install app / Add to Home screen
Drivers don't need the app: the manager sends their trips by WhatsApp or SMS.

BACKUPS
Records stay on the phone only. Use Backup & restore every week and keep the file
on WhatsApp, Google Drive or iCloud. To move to a new phone, activate the app on the
new phone and restore the latest backup file.

UPDATING THE APP
Replace the files on the website. Phones pick up the new version the next time
the app is opened, and their records are kept.
If you change sw.js, also change the version name in its first line (fleet-manager-v1 to v2).
