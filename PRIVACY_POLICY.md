# Privacy Policy for IWallet

**Last updated:** 09/11/2026

IWallet ("the app") is a personal income and expense tracker developed by Dani ("the developer"). This policy explains what information the app handles, where it goes, and what choices you have. Spanish version: [PRIVACY_POLICY.es.md](PRIVACY_POLICY.es.md).

## 1. Data stored on your device

All your financial data (transactions, categories, concepts, limits, notes), your settings and your access PIN are stored **only on your device**, in the app's private storage. The app has no user accounts and no developer-operated server that stores your financial data. The developer cannot see it.

* **Access PIN:** stored as a hash (SHA-256), not in plain text.
* **Gemini API key (optional):** if you enter your own key, it is stored locally on your device.
* **Backups:** the app opts out of Android automatic cloud backup. Your data is not copied to Google Drive by the app. If you uninstall the app, its local data is deleted by the operating system. You can export your transactions to a CSV file at any time. You can delete any transaction from the Global tab by swiping it; deleted transactions go to the Trash (Settings > Trash), where you can restore them or delete them permanently, and they are removed automatically after 7 days. Categories and concepts can be edited or deleted from Settings. To remove all data at once, see section 6.

## 2. Permissions

* **Camera / gallery (through the system picker):** to capture or choose a receipt image.
* **Microphone:** for voice entry of transactions.
* **Internet:** for the optional features described below.

## 3. Features that send data outside your device

**a) Receipt scanning with cloud AI (optional, off by default).** By default receipts are read locally on your device with Google ML Kit and the image does not leave your phone. If you choose to enter your own Google Gemini API key in Settings, the receipt image is sent to Google's Gemini API to extract the merchant, date and amount. Google processes it under its own terms: https://policies.google.com/privacy. If the cloud request fails, the app falls back to local reading and tells you.

**b) Voice entry.** Voice recognition uses the speech recognition service of your Android device, which is provided by Google and may process audio on Google's servers depending on your device settings. The app does not store the audio; it only receives the recognized text.

**c) "Coming soon" form (optional).** If you open the "Coming soon" form about upcoming features, you may choose to send:
* your **email address** (only if you decide to enter it),
* which upcoming features interest you,
* a **free-text suggestion**,
* the fact that you accepted this policy.

This information is sent over HTTPS to a Google Apps Script endpoint and stored in a private Google Sheet that **only the developer can access**. Purpose: to notify you when the features you selected are available and to improve the app. Legal basis: your consent (you must tick the acceptance box). It is retained until the features launch or you ask for deletion. You can withdraw consent and request deletion at any time by emailing the contact address below. Please do not include sensitive personal data in the free-text suggestion.

## 4. Advertising and tracking

The app contains no advertising and no analytics or tracking tools, and the developer does not sell or share your information with advertisers.

## 5. Your rights

If you are in the European Economic Area or another region with similar laws, you have the right to access, correct, delete or restrict the data described in section 3c, and to withdraw consent. Contact the developer at the address below.

## 6. How to delete your data

**Data on your device** (transactions, pending items, categories, concepts, limits, settings, PIN). You can delete it yourself at any time:

1. Open **Settings > Backup and data > Start from scratch** and confirm by typing DELETE. This deletes all transactions, pending items and the trash. Categories, concepts, limits, settings, your PIN and your Gemini key are kept; you can edit or delete them from Settings.
2. Or uninstall the app, or clear its storage in Android settings, to remove everything.

The developer cannot see or delete this data, because it never leaves your device.

**Data you sent through the "Coming soon" form** (email address, selected features, suggestion text). To ask for its deletion, email dsalcedocias@gmail.com with the subject "Delete my IWallet data", from the address you used in the form (or mention it in the message). It will be deleted from the private Google Sheet within 30 days and you will get a confirmation by email. If you make no request, it is kept until the features you selected launch.

**Receipt photos sent to Gemini** (only if you enter your own Gemini key). IWallet does not keep them: the app deletes the photo from its cache after processing it. The copy sent to Google's Gemini API is handled under Google's own terms: https://policies.google.com/privacy.

**Voice.** IWallet does not store audio. Voice recognition is handled by your device's Android speech service, under your device and Google account settings.

## 7. Children

The app is not directed to children under 13 (or the minimum age in your country).

## 8. Changes to this policy

If the app changes in a way that affects your data (for example cloud sync or paid plans), this policy will be updated and the date above changed.

## 9. Contact

dsalcedocias@gmail.com
