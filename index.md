---
layout: default
title: Keepla Privacy Policy
---

# Keepla Privacy Policy

Effective date: 14 July 2026

Developer: Eren Avar

Privacy contact: [erenavar@gmail.com](mailto:erenavar@gmail.com)

Public policy URL: [https://erenavar.github.io/keepla-privacy/](https://erenavar.github.io/keepla-privacy/)

## Overview

Keepla is a local-first reminder application for pet care and everyday plans. It does not require an
account and does not include advertising or product-behavior tracking SDKs. Reminder content is encrypted and stored
on the user's device. This policy explains the limited technical data used to deliver app updates and
the information that remains under the user's control on the device.

## Information Stored Only On The Device

Keepla stores pet profiles, selected pet profile photos, reminder titles, notes, dates, completion
history, notification preferences, security settings, and language preferences locally. On supported
mobile platforms, record content and selected photos are encrypted before being written to the local
database. The encryption key is held in the device's secure storage.

The developer does not receive this content. Local processing is not collection by the developer.

## Photos, Biometrics, And Notifications

- On Android, Keepla uses the system photo picker. The app receives only the pet profile photo the user
  selects and does not request broad photo-library access, camera access, microphone access, contacts,
  or location.
- On iOS, the system photo-selection flow and its permission notice are used. Keepla processes only the
  selected image for the pet profile.
- Biometric or device authentication is performed by the operating system. Keepla receives only the
  success or failure result and never receives biometric templates.
- Reminder notifications are scheduled locally through the operating system. The user can use private
  notification text so reminder titles and pet names do not appear on the lock screen.

## Encrypted Backups

Backups are created only when the user requests them. They are encrypted with a password chosen by the
user. Keepla does not store or recover that password. Export and import use the operating system's file
picker or share sheet, so any destination selected by the user is governed by that destination's terms
and privacy practices. Keepla does not automatically upload backups.

## App Updates And Technical Data

Keepla uses Expo Application Services (EAS) Update to check for and deliver compatible app updates over
HTTPS. Expo may process network information such as the IP address, device operating-system information,
app/update version information, and a randomized installation token needed to decide which update to
deliver and to operate staged rollouts. Expo may also process update download, installation and launch
events, project usage statistics, technical errors, and update-service performance metrics to operate,
secure, troubleshoot, and improve the service. This technical processing does not include Keepla
reminder titles, notes, pet names, selected pet photos, or backup contents.

Keepla uses Expo as a service provider for this update delivery. Its processing is described in the
[Expo Privacy Policy](https://expo.dev/privacy).

## Error Reports

The current production configuration has no error-reporting endpoint and therefore sends no app-owned
error reports. Keepla contains a disabled-by-default privacy-safe reporting capability for a future
release. It must not be activated in production until this policy and the applicable store Data Safety
declaration are updated. Even when enabled, the report format excludes raw error messages, reminder
content, pet names, notes, backup content, and record identifiers.

## Sharing, Sale, And Advertising

Keepla does not sell personal data. It does not use personal data for advertising or cross-app tracking.
The limited update-delivery data described above is processed by Expo to provide the update service and
is not shared for Expo's independent advertising purposes by Keepla.

## Retention And Deletion

Local records remain on the device until the user deletes individual items, securely wipes the Keepla
vault, or removes the app. A secure wipe removes the local encrypted vault, settings, notification
schedules, and device-held vault key. Removing the app also removes its app-private local data, subject
to operating-system behavior.

Technical update-service data is retained by Expo according to Expo's retention practices. Contact the
developer through the privacy contact above for privacy questions concerning Keepla. Because Keepla has
no account system or developer-hosted user database, the developer cannot remotely identify or erase
local reminder content from a user's device.

## Children

Keepla is not designed for children and does not knowingly collect children's reminder content. Parents
or guardians who believe a child has provided technical data through the update service may contact the
developer using the privacy contact above.

## Medical And Veterinary Disclaimer

Keepla is a reminder tool. It is not a medical device and does not provide veterinary diagnosis,
treatment, or emergency guidance. Users should consult a qualified veterinarian for medical decisions.

## Security

Keepla uses device-local encryption, secure key storage, HTTPS update transport, optional app locking,
screen-capture protection, private notification text, and encrypted backups. No system can guarantee
absolute security, but Keepla limits collection and access by design.

## Changes To This Policy

This policy will be updated before Keepla introduces a new collection purpose, processor, account
system, analytics service, advertising service, or production error-reporting endpoint. Material changes
will be reflected by an updated effective date and made available at the public policy URL.
