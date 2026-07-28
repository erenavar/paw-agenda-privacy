---
layout: default
title: Paw Agenda Privacy Policy
---

# Paw Agenda Privacy Policy

Effective date: 28 July 2026

Developer: Eren Avar

Privacy contact: [erenavar@gmail.com](mailto:erenavar@gmail.com)

Public policy URL: [https://erenavar.github.io/paw-agenda-privacy/](https://erenavar.github.io/paw-agenda-privacy/)

## Overview

Paw Agenda is a local-first reminder application for pet care and everyday plans. It does not require a
Paw Agenda account and does not include advertising or product-behavior tracking SDKs. It offers an optional
one-time Plus Lifetime in-app purchase, processed by the Apple App Store or Google Play. Reminder content is
encrypted and stored on the user's device. This policy explains the limited technical data used to deliver app
updates and the information that remains under the user’s control on the device.

## Information Stored Only On The Device

Paw Agenda stores pet profiles, selected pet profile photos, reminder titles, notes, dates, completion
history, notification preferences, security settings, and language preferences locally. On supported
mobile platforms, record content and selected photos are encrypted before being written to the local
database. The encryption key is held in the device's secure storage.

The developer does not receive this content. Local processing is not collection by the developer.

## Photos, Biometrics, And Notifications

- On Android, Paw Agenda uses the system photo picker. The app receives only the pet profile photo the user
  selects and does not request broad photo-library access, camera access, microphone access, contacts,
  or location.
- On iOS, the system photo-selection flow and its permission notice are used. Paw Agenda processes only the
  selected image for the pet profile.
- Biometric or device authentication is performed by the operating system. Paw Agenda receives only the
  success or failure result and never receives biometric templates.
- Reminder notifications are scheduled locally through the operating system. The user can use private
  notification text so reminder titles and pet names do not appear on the lock screen.

## Encrypted Backups

Backups are created only when the user requests them. They are encrypted with a password chosen by the
user. Paw Agenda does not store or recover that password. Export and import use the operating system's file
picker or share sheet, so any destination selected by the user is governed by that destination's terms
and privacy practices. Paw Agenda does not automatically upload backups.

## Plus Lifetime Purchase

Plus Lifetime is a personal, non-consumable in-app purchase. Apple or Google processes the payment, maintains
the purchase history for the relevant store account, and handles the payment method. Paw Agenda does not ask for,
receive, or store payment-card details. The app asks the relevant store on the device to confirm that the exact
Plus Lifetime product belongs to the currently signed-in store account; it does not create a Paw Agenda user
account or a developer-hosted purchase database.

The purchase can be restored only on the purchaser's own devices using the same Apple ID or Google account.
Encrypted backup files contain local records but do not carry a Plus entitlement. Family Sharing is not enabled
for this product. Apple and Google each manage purchases in their own stores, so a purchase does not automatically
move between those stores when a user changes platform.

## App Updates And Technical Data

Paw Agenda uses Expo Application Services (EAS) Update to check for and deliver compatible app updates over
HTTPS. Expo may process network information such as the IP address, device operating-system information,
app/update version information, and a randomized installation token needed to decide which update to
deliver and to operate staged rollouts. Expo may also process update download, installation and launch
events, project usage statistics, technical errors, and update-service performance metrics to operate,
secure, troubleshoot, and improve the service. This technical processing does not include Paw Agenda
reminder titles, notes, pet names, selected pet photos, or backup contents.

Paw Agenda uses Expo as a service provider for this update delivery. Its processing is described in the
[Expo Privacy Policy](https://expo.dev/privacy).

## Error Reports

The current production configuration has no error-reporting endpoint and therefore sends no app-owned
error reports. Paw Agenda contains a disabled-by-default privacy-safe reporting capability for a future
release. It must not be activated in production until this policy and the applicable store Data Safety
declaration are updated. Even when enabled, the report format excludes raw error messages, reminder
content, pet names, notes, backup content, and record identifiers.

## Sharing, Sale, And Advertising

Paw Agenda does not sell personal data. It does not use personal data for advertising or cross-app tracking.
The limited update-delivery data described above is processed by Expo to provide the update service and
is not shared for Expo's independent advertising purposes by Paw Agenda.

## Retention And Deletion

Local records remain on the device until the user deletes individual items, securely wipes the Paw Agenda
vault, or removes the app. A secure wipe removes the local encrypted vault, settings, notification
schedules, and device-held vault key. Removing the app also removes its app-private local data, subject
to operating-system behavior.

Technical update-service data is retained by Expo according to Expo's retention practices. Contact the
developer through the privacy contact above for privacy questions concerning Paw Agenda. Because Paw Agenda
has no account system or developer-hosted user database, the developer cannot remotely identify or erase
local reminder content from a user's device.

## Children And Families

Paw Agenda is intended for users aged 9 and older, including children, teenagers, and adults. Children may
use it to help manage pet-care responsibilities, preferably with guidance from a parent or guardian. The app
does not create accounts, display ads, or enable communication between users. Its optional one-time Plus
Lifetime purchase is processed only by the platform's store payment flow. Children's pet profiles, selected
photos, reminders, and notes remain encrypted on the device and are not sent to the developer.

The limited technical data described in "App Updates And Technical Data" may be processed by Expo solely to
deliver, secure, and measure app updates. Paw Agenda does not use this data for advertising, behavioral
profiling, or cross-app tracking. A parent or guardian may contact the developer using the privacy contact
above with questions about a child's use of Paw Agenda.

## Medical And Veterinary Disclaimer

Paw Agenda is a reminder tool. It is not a medical device and does not provide veterinary diagnosis,
treatment, or emergency guidance. Users should consult a qualified veterinarian for medical decisions.

## Security

Paw Agenda uses device-local encryption, secure key storage, HTTPS update transport, optional app locking,
screen-capture protection, private notification text, and encrypted backups. No system can guarantee
absolute security, but Paw Agenda limits collection and access by design.

## Changes To This Policy

This policy will be updated before Paw Agenda introduces a new collection purpose, processor, account
system, analytics service, advertising service, or production error-reporting endpoint. Material changes
will be reflected by an updated effective date and made available at the public policy URL.
