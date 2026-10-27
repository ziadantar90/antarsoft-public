# Badna privacy policy

Effective `[EFFECTIVE_DATE]`. Version 1.

Badna is a shopping-list app for households and groups. This policy explains what personal data we collect when you use it, why we collect it, who we share it with, how long we keep it and what you can do about it. We wrote it in plain language. If a sentence is unclear, write to us and we will explain.

## 1. Who we are

Ziad Antar, trading as Antarsoft, Dafan, Ras Al Khaimah, United Arab Emirates, publishes Badna and is the data controller for the personal data described here.

Write to hello@antarsoft.dev for anything in this policy. We do not have a data protection officer, because we do not process data at a scale that requires one. `[EU_REPRESENTATIVE_LINE]`

## 2. What this policy covers

This policy covers the Badna app on iOS, Android and the web, and our website at `[SITE_URL]`. It does not cover the App Store or Google Play themselves, or the payment you make there. Apple and Google handle those under their own privacy policies.

## 3. What we collect, and why

The table lists everything. Under GDPR we need a legal reason for each use; the last column gives it.

| What | Where it comes from | Why we use it | Legal reason |
| --- | --- | --- | --- |
| Your email address and password | You, when you create an account with email and password | To sign you in, to let people invite you to a list by email, and to answer your messages. Firebase stores the password as a hash; we never see it | Running your account (contract) |
| Your Apple or Google sign-in | Apple or Google, when you create an account or sign in with them | We receive a signed token that proves who you are, your email address and your name, and Firebase keeps them in your sign-in record. Apple sends your name only the first time, and sends a hidden relay address instead of your email if you choose to hide it; mail we send to a relay address is forwarded to you by Apple. Google also sends a link to the picture on your Google account, which Firebase keeps in that record and we do not show. We never receive your Apple or Google password | Contract |
| Use without an account | You, when you tap Get started without creating an account | We create an account id for you with no email, so your lists can sync and be kept. You cannot share lists, join lists or subscribe until you create an account. When you create one, your lists stay with you; when you instead sign in to an account you already have, we move your lists into it and delete the account id we made for you. We delete the account id and its lists after `[GUEST_RETENTION_DAYS]` days without you opening the app, or sooner when you delete your data in Profile (section 8) | Contract |
| Your display name | You. It starts as the part of your email before the @, or as the name Apple or Google sent us, and you can change it on Profile | To show who added what on a shared list | Contract |
| Your account id | Created by Firebase when you first use the app, with or without an account | To link everything below to your account. It is a random string, not your name | Contract |
| Your lists and items | You and the other members of your lists | This is the product: list names and icons, item names, quantities, units, categories, done flags and order, and who added each item. It also includes the names of the stores a list keeps and the order its categories are shown in for the list and for each store | Contract |
| Who is on which list, and with which role | The list owner, by inviting people | To give members access to a list and to nobody else | Contract |
| An email address you type into an invite | You | To find that person's account and add them to your list. We use it for nothing else | Our legitimate interest in letting you share lists, and the invitee's interest in being asked |
| Your plan (Free or Pro) and usage counters | Our servers, from your subscription and your activity | To apply the Free limits and unlock Pro | Contract |
| Your subscription | RevenueCat, the service that reads your App Store or Google Play purchase | To know whether you have Pro, to handle refunds and renewals, and to help with billing questions. We get the product, the dates and the price in your store's currency. We never get your card number or billing address | Contract; legal obligation to keep accounting records |
| Device and connection data | Your device, through the Firebase, RevenueCat and Expo SDKs | IP address, device model and operating system, app version and language. Used to keep the service secure, to deliver app updates and to diagnose problems | Our legitimate interest in running a secure, working service |
| Your notification token and app language | Your phone, when you allow notifications | To tell you when someone adds items to a list you share. The token is a random string that Google and, on an iPhone, Apple use to reach your phone; it is not your phone number. We keep one token for each phone on which you allowed notifications, with the language you chose in the app, so the notification arrives in that language | Contract. Notifications are optional: you can turn them off in your phone's settings, or mute a list in the app |
| Crash reports | The Firebase Crashlytics SDK on your device, when the app crashes | The stack trace, the device model and OS, the app version and your account id. Used to fix crashes. Never your email, name or IP address | Legitimate interest in fixing bugs |
| Product analytics | The Google Analytics for Firebase SDK on your device | Which features you use, with platform, app version, language and plan, tied to your phone's app install and not to your account. Used to learn which features matter and to tune the Free limits. Never your email, name or IP address; no advertising id; no session recording | Legitimate interest in improving the app, or your consent where the law where you live requires it (section 9) |
| Your voice, only while you add items by voice | You, when you tap the microphone in the new item sheet | Your phone's own speech recognition turns what you say into item names: Apple's on an iPhone, Google's or your phone maker's on Android. Where the phone can, this happens on the phone; otherwise the phone sends the audio to Apple or Google under their own terms. We never receive or keep the audio; only the items you then add are saved, as if you had typed them | We do not process the audio; the items you add are covered by "Your lists and items" (contract) |
| Support messages | You, when you write to us | To answer you. The app's prefilled email includes your account id and email so we can find your account | Contract; legal obligation for deletion requests |

We do not collect your location, contacts, photos, recordings of your voice, advertising identifier or payment card details, and we collect no health or other sensitive data. The app has no ads, and we do not track you across other apps or websites.

**What you have to provide.** You can use Badna without an account, and then nothing is required of you; the lists you make are saved under an account id we create for you and are deleted after `[GUEST_RETENTION_DAYS]` days without you opening the app (section 7). To create an account, and to share lists, join lists or subscribe, you need an email address with a password, or an Apple or Google account. Everything else is optional or comes from using the app.

## 4. What other people on your lists can see

Shopping lists are shared, so some of your data is visible to the other members of each list you are on:

- your display name and your account id,
- the items you add, edit or tick off,
- the stores you add to a list and the order you arrange its categories in.

Members cannot see your email address, your plan or your other lists. If you type someone's email address into an invite, we use it once to find their account, and we tell them who invited them.

When you add items to a shared list, we send the other members a notification on their phones that names you and the items, unless they have not allowed notifications or have muted that list. You get no notification about your own changes. You can mute any list from inside the app, which changes nothing for the other members, and you can turn notifications off for the whole app in your phone's settings.

## 5. Who we share data with

We share personal data only with the companies that help us run the app. Each one processes data under our instructions and under a data processing agreement that requires it to protect your data at least as well as this policy promises. We do not sell personal data, and we do not share it for advertising.

| Company | What it does for us | What it holds |
| --- | --- | --- |
| Google LLC (Firebase, Google Cloud) | Sign-in, the database, our server code, hosting, and sending our notifications to your phone | Your account, including the email, name and account identifier Apple or Google sent when you signed in with them, your lists and items, server logs with your account id, your notification tokens, and the text of each notification until your phone receives it, or four weeks at most |
| RevenueCat, Inc. | Reads your App Store or Google Play purchase and tells us whether you have Pro | Your account id, your store receipt or purchase token, device type and OS, the subscription's product, dates and price |
| Expo (650 Industries, Inc.) | Builds the app and delivers app updates | Platform, app version and a random token on each update check; not your account id |
| Google LLC: Firebase Crashlytics | Crash reporting | Crash reports with your account id |
| Google LLC: Google Analytics for Firebase | Product analytics | Usage events tied to the app install, not to your account |
| `[EMAIL_PROVIDER]` | Our support mailbox | What you write to us |

The current list, with each company's location and terms, is kept in our data inventory at `[DATA_INVENTORY_URL]`. We update it when we add or change a provider.

Apple and Google are not on this list for the stores: they run the stores and handle your payment as independent controllers under their own policies. When you sign in with Apple or Google, the sign-in itself also happens under their own privacy policy: they learn that you signed in to Badna, and the sign-in tells them nothing about your lists. On an iPhone, a notification reaches you through Apple's push notification service: Google hands Apple the text of the notification and your phone's token, and Apple delivers it under the terms it sets for every app on the App Store.

We may also disclose data when the law requires it, for example to answer a valid order from a court or authority, and to a buyer if the app changes hands, in which case this policy still applies to your data and we tell you first.

## 6. Where your data is stored

Your account, your lists and your notification settings are stored in Google's data centres in `[FIRESTORE_LOCATION]`. Firebase sign-in runs in the United States. Crash reports and analytics events go to Google, which may process them in any of its data centres. RevenueCat and Expo run in the United States. Notifications pass through Google's and, on an iPhone, Apple's push services, which may handle them in any of their data centres.

If you live in the European Economic Area, the United Kingdom or Switzerland, some of your data therefore leaves your region. We rely on the EU-US Data Privacy Framework where the provider is certified under it (Google, Expo) and on the European Commission's Standard Contractual Clauses, with the UK and Swiss addenda, for the rest (RevenueCat). Write to us if you want a copy of the safeguards.

## 7. How long we keep data

| Data | Kept until |
| --- | --- |
| Your account, your lists and your membership of other people's lists | You delete your account, or ask us to (section 8) |
| Lists you make without an account, and the account id we created for them | `[GUEST_RETENTION_DAYS]` days after you last opened the app, unless you delete your data in Profile first, create an account, which keeps them, or sign in to an existing account, which moves them into it (section 3) |
| The record we keep while moving lists from an account id without email into your account | Until the move finishes, normally within seconds; a scheduled job finishes any move that stalls within a few hours |
| Items you added to a list someone else owns | That list's owner or any editor deletes them; after you delete your account they are no longer marked as added by you |
| Your usage counters | Reset every usage period; deleted with the account |
| Your notification tokens | Each token until you sign out on that phone, until Google tells us it no longer works (a token stops working when you remove the app or your phone has not connected to Google for a long time), or until you delete your account. If your phone has no connection when you sign out, the sign-out still goes through, but the token keeps working until the app next opens on that phone with a connection; our copy goes when you next sign in on that phone, or when a notification we send after that fails to reach it |
| A notification waiting for your phone | Until your phone receives it, or four weeks at most |
| The items you just added, kept for a moment so that several adds become one notification | Until the notification is sent, normally within a minute. If it could not be sent, until the next time you add to that list, so they go out with that notification, or until the list is deleted |
| Which lists you muted | Until you delete your account |
| Subscription records at RevenueCat | Deleted with your account. Apple and Google keep the purchase itself under their own policies |
| Server logs (account ids, never names or emails) | 30 days |
| Crash reports | 90 days |
| Analytics events | 2 months. They are not tied to your account, so deleting the account does not change them |
| Webhook records that stop a purchase being counted twice | 90 days |
| Pending invites | Until accepted, or 7 days |
| Support emails | 12 months after we close the conversation. If you asked us to delete your account, we keep that email thread for 24 months as the record that we did it |
| Backups | Up to 90 days, then they expire. Beside each copy we keep a list of deleted account ids, so that a deleted account stays deleted. Backups are restored only after a data-loss incident, and we apply every deletion again afterwards |

## 8. Deleting your account

You can delete your account inside the app or by email. Deletion is immediate and cannot be undone.

**In the app.** Open Profile, then Account & data, then Delete account. You will be asked to sign in again if your last sign-in was more than five minutes ago, with your password or with the Apple or Google account you use, and to type a confirmation. If you use Badna without an account, open Profile and tap Delete my data; nothing more is asked, because the app on your device is the only key to that data.

**By email.** Write to hello@antarsoft.dev from the email address you use in the app. We reply to that address and ask you to confirm. We delete the account within five business days of your confirmation and reply when it is done. We cannot act on requests from a different address, because we have no other way to check that the account is yours. Full details are at `[DELETION_URL]`.

**If you signed in with Apple.** When you delete your account in the app, we also ask Apple to disconnect Badna from your Apple Account. If that request fails, the deletion still goes ahead, and you can remove Badna yourself under Sign in with Apple in your Apple Account settings. We never store the Apple tokens this needs.

**If you use Badna without an account.** We hold no email address for you, so we cannot find your data from a message; delete it from Profile in the app. Lists you make without an account are in any case deleted after `[GUEST_RETENTION_DAYS]` days without you opening the app.

**What is deleted.** Your profile (email, display name, plan and usage counters), the notification tokens of your phones and your notification settings, every list you own and everything in it, your membership of lists other people own, your login, your RevenueCat record and your analytics events.

**What is not deleted.** Lists other people own, including items you added to them; after deletion those items are marked as added by a former member, not by you. Your subscription: deleting your account does not cancel it, so cancel it first in the App Store or Google Play. Your purchase history, which Apple and Google keep. Your Apple or Google account itself, which Apple and Google keep; if we could not disconnect Badna from it, you can do so in its settings. Copies in our backups and crash reports, which expire on the schedule in section 7.

## 9. Your rights

Wherever you live, you can ask us to:

- **See** the personal data we hold about you, and get a copy in a machine-readable form.
- **Correct** it. You can change your display name on Profile and your password from the sign-in screen; write to us for anything else.
- **Delete** it (section 8).
- **Restrict or object** to a use of it that rests on our legitimate interests, such as analytics or crash reporting.
- **Withdraw consent** where we asked for it, for example for analytics in countries that require consent. Turn it off in Profile under Privacy, or write to us. Withdrawing consent does not affect what happened before.

To use a right, write to hello@antarsoft.dev from the email address on your account. That address is how we check that the request is yours; we never ask for a copy of your ID. If you use Badna without an account, we have no address to check a request against, so the right we can act on is deletion, from Profile in the app; the other rights become available once you create an account, which keeps your lists. We answer within one month. If a request is unusually complex we may take up to two more months, and we tell you why before the first month ends. Exercising a right costs nothing and never changes how we treat you.

If you live in the European Economic Area, the United Kingdom or Switzerland, you also have the right to complain to a data protection authority. Ours is `[SUPERVISORY_AUTHORITY]`; you can also complain to the authority where you live.

We make no decisions about you by automated means that have legal or similarly significant effects. The Free limits are applied the same way to every Free account and are described in the app.

## 10. If you live in California

The California Consumer Privacy Act (CCPA) applies to businesses above certain size thresholds. Whether or not it applies to us, we give California residents the rights it describes.

In the last twelve months we have collected these categories of personal information, as the CCPA names them: identifiers (email address, account id, the identifier Apple or Google gives us when you sign in with them, IP address, push notification token); internet or electronic network activity (how you use the app, crash reports); commercial information (your subscription); and the content you create, meaning your lists, which the CCPA does not name as a category but which we list so nothing is left out. The sources and purposes are in section 3. We do not collect sensitive personal information as the CCPA defines it.

We have not sold or shared personal information, in the CCPA's meaning of those words, in the last twelve months, and we do not do so. We disclose personal information to the service providers in section 5 for the business purposes in section 3 only.

You have the right to know what we collect, to delete it, to correct it, and to not be discriminated against for using these rights. Because we operate only online, you submit a request by email to hello@antarsoft.dev or from the Account & data screen in the app. We confirm the request is yours by replying to the email address on your account, and we respond within 45 days. You can also have an agent act for you if you give them written permission and we can confirm your identity.

## 11. Children

Badna is not for children under 13, or under 16 where the law where you live sets that age. We do not knowingly collect personal data from children. If you believe a child has created an account, write to us and we will delete it.

## 12. How we protect your data

Every connection between the app and our servers is encrypted. Access to your data is enforced by database security rules that check who you are on every read and write; the rules are tested before every release. Only the person who runs the service has access to the production systems, and never from the app. Passwords are hashed by Firebase Authentication and we cannot read them, and when you sign in with Apple or Google we never receive your Apple or Google password. Crash and analytics data carry your account id but never your email or IP address. If a breach ever affects your data, we tell you and the relevant authority as the law requires.

## 13. Cookies and the web version

The iOS and Android apps use no cookies. The web version of the app and our website use the cookies and local storage needed to keep you signed in and remember your language, which need no consent. Where our website uses analytics cookies, we ask for your consent first if the law where you are requires it, and you can change your choice from the link in the site footer.

## 14. Changes to this policy

When we change this policy, we update the version and effective date at the top and keep earlier versions at `[PRIVACY_POLICY_URL]`. If a change affects what we collect or how we use it, we tell you in the app at least 30 days before it takes effect, or sooner if the law requires it.

## 15. Contact

Ziad Antar, trading as Antarsoft
Dafan, Ras Al Khaimah, United Arab Emirates
hello@antarsoft.dev

This policy is written in English. The Arabic and Russian translations are provided for convenience; if they differ from the English text, the English text applies.
