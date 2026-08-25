---
layout: doc
title: Privacy Policy
updated: Last updated 22 August 2026.
description: What the Room8 TestFlight beta collects, who processes it, and how long it is kept.
next_title: Terms of Service
next_url: terms.html
---

## 1. What we collect, and why

Every category below corresponds to data the app actually stores.

| Category | Examples | Why |
| --- | --- | --- |
| Account | Name, email, username, date of birth, phone, password handled by Supabase | Create and secure your account; confirm you are old enough |
| Profile | Photo, pronouns, gender, bio, interests, university, major, graduation year, lifestyle answers, links, payment handles | Show you to your household; entirely optional beyond name and email |
| Household | Group name, address or location, membership, roles | Group people who live together |
| Messages | Message text, photos, files, voice notes, reactions, read state | Deliver conversations to your household |
| Calendar & chores | Events, chores, assignments, reminders, swaps, nudges | Run the shared calendar |
| Connected calendar | Feed URL (secret), the next few weeks of events, sync time | Show your household when you are busy |
| Money records | Debts, balances, recurring payments, split acceptances, disputes | Track what roommates owe each other. No payments are processed. |
| Receipts | Receipt photo, store name and address, items, totals, date, payment method string | Turn a photo into an itemised split |
| Shopping & inventory | Items, quantities, categories, costs, who added and who bought | Run the shared list |
| Device | Push token, device id, platform, last seen | Send notifications you have enabled |

### Sensitive categories, named explicitly

Some laws treat these differently, so they are called out rather than buried: date of birth, your home location, private messages and photos, education details, financial handles and purchase history, and the contents of a connected calendar. We do not sell any of it and we do not use it for advertising.

## 2. Who else processes your data

We do not sell your personal information. We share it with these providers so the app can work:

| Provider | What it handles | Where |
| --- | --- | --- |
| Supabase | Sign-in, and the database holding everything above | United States |
| Amazon S3 | Photos, receipts and message attachments | United States |
| Amazon SES | Account emails — verification codes, address changes | United States |
| Expo | Delivering push notifications to your device | United States |
| OpenAI | Receipt images you upload are sent to OpenAI to read the text. Only receipts — never messages, profiles or calendars. | United States |

We may also disclose data where the law requires it, or to protect someone's safety or our rights.

## 3. How long we keep it

Account and household data is kept while your account is open. Messages and household records persist for the household even after an individual leaves, because they belong to the shared history. Connected-calendar events are replaced on every sync and only ever cover the coming weeks.

When you delete your account, everything that identifies you is erased immediately — name, photo, bio, contact details, links, payment handles, calendar and lifestyle answers — and your devices stop receiving notifications. What stays is an anonymous placeholder, because messages you sent and balances involving other people are also part of their record; you appear to them as a deleted account.

Your sign-in record is removed separately, by an automated weekly cleanup, so it can persist for up to seven days after the rest is gone. It grants access to nothing in the meantime. Routine backups age out on their own cycle.

## 4. Your rights

Depending on where you live, you may have the right to access a copy of your data, correct it, delete it, object to or restrict processing, take it elsewhere in a portable form, and to be free from discrimination for exercising any of these. Residents of California, and of the EU and UK, have these rights by statute; we extend them to everyone.

Delete your account yourself from Settings → Danger Zone → Delete account. For anything else, write to [support@room8.xyz](mailto:support@room8.xyz), marking the subject "Privacy request" so it is routed correctly. We respond within 45 DAYS — CCPA'S LIMIT.

## 5. Children

Room8 is not for children under 13 and we do not knowingly collect their information. If we learn we have, we delete it. If you believe a child has registered, write to [support@room8.xyz](mailto:support@room8.xyz).

## 6. Security

Data is encrypted in transit. Files are stored in a private bucket reachable only through time-limited links. Authentication is handled by Supabase and we never store your password. No system is perfectly secure, and we cannot guarantee absolute security.

## 7. Changes and contact

We will notify you in the app before a material change takes effect. Room8 is run by two individuals, not a company, and has no business premises; the controller of your data is FELIX PANTOJA and EDELSON GARCIA, reachable at [support@room8.xyz](mailto:support@room8.xyz).
