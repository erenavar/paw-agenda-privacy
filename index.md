---
layout: default
title: Paw Agenda Privacy Policy
---

# Paw Agenda Privacy Policy

Effective date: 1 October 2026

Scope: local pet-care records and optional features in the next iOS version, 1.2.0. Analytics is part of that native iOS binary only; previously published versions do not acquire it through this policy or a server setting. Android publication is outside this update.

Developer: Eren Avar

Privacy contact: [erenavar@gmail.com](mailto:erenavar@gmail.com)

Public policy URL: [Paw Agenda Privacy Policy](https://erenavar.github.io/paw-agenda-privacy/)

## Overview

Paw Agenda helps users record pet care, health history and reminders. It does not require a registered Paw Agenda account or display ads. Pet records and selected files are stored locally in an encrypted vault. iOS 1.2.0 includes optional Firebase Analytics, with the adult eligibility and permission controls described below. The app also uses operating-system notifications, file selection, sharing, anonymous technical authentication and optional store purchases. Temporary export files, the optional widget count and live caregiver sharing have the separate handling described below.

## Records Stored On The Device

Local records include pet profiles and selected photos; care-journal entries and food, water, activity-duration and weight measurements; health-passport notes and selected documents; reminder schedules, routine links and completion history; and notification, security, language and appearance preferences. Records and selected document contents are encrypted before being written to the local database. The vault key is held in the device's secure storage. Paw Agenda does not upload these records to the developer or operate general cloud synchronization. The deliberately limited, encrypted routine payload used for live caregiver sharing is described below.

Charts and period comparisons are calculated from the measurements entered on the device. They do not involve an external analysis service.

## Planned Care Routines

The user chooses a care template, date, time and repeat interval, or links a suitable existing reminder. A completed plan either creates a care-journal entry or links an entry the user explicitly selects. The planned occurrence and actual care record are stored together in the encrypted vault and included in password-protected backups. Deleting a plan does not automatically delete historical care entries; deleting a care entry does not reverse the reminder's completion history.

## Optional Plus Plans And Payments

Paw Agenda offers a monthly auto-renewing subscription, a yearly auto-renewing subscription and a one-time Plus Lifetime purchase. All three plans provide the same Plus features: unlimited pet profiles and active reminders per pet, all visual themes, measurement charts and period comparisons, PDF veterinarian summaries, document-archive additions, sitter handoff PDF sharing, live caregiver sharing and the optional widget count. Basic care and measurement logging, routine templates, existing-record access, plain-text veterinarian summaries, pet cards and the widget shortcut remain available without Plus, subject to the displayed Free profile and reminder limits. Document capacity limits still apply with Plus. Saved archive documents remain accessible, exportable and deletable after Plus ends. The invited caregiver does not need Plus to use a list that an owner has shared.

Apple or Google processes payment and maintains the applicable store purchase history. Paw Agenda does not ask for, receive or store payment-card information. The app queries the store on the device to confirm purchase rights; it does not operate a developer-hosted purchase database or send pet records, photos, documents or backup contents to the store for this purpose.

Subscriptions renew automatically unless cancelled in the purchaser's Apple or Google account settings. Access continues for the paid subscription period. Plus Lifetime is a personal, non-consumable licence restored with the same store account used for purchase. Family Sharing is not enabled for the Apple Lifetime product. Backup files do not transfer purchase rights, and purchases do not automatically transfer between Apple and Google stores. Prices and purchase terms are displayed by the applicable store.

## Photos, File Selection, Biometrics And Notifications

- The app processes the pet profile photo the user selects through the system photo-selection flow. Android uses the system photo picker without broad photo-library access. iOS uses its system selection flow and permission notice.
- A system document picker lets the user select a PDF, JPEG or PNG file. The selected provider may download a file from the user's own storage service. This is not Paw Agenda cloud synchronization. The app does not request access to the user's contacts, location, camera or microphone.
- Authentication is performed by the operating system. Paw Agenda receives the success or failure result, not biometric templates.
- Reminder notifications are scheduled locally. The operating system receives the content needed to display them. The private-text setting replaces pet names and reminder titles with generic text on the notification surface. The app does not register for remote push notifications for these features.

## Encrypted Backups

Backups are created on request and protected with a password chosen by the user. Paw Agenda does not store or recover that password. They include the supported local pet, reminder, care and health records, selected documents and routine links. The next feature release creates v7 backups and accepts v1–v6 backups. Widget snapshots, Analytics age/permission choices, Analytics installation identifiers and Plus purchase rights are not included.

The user selects a destination through the operating system's directory picker or share sheet and selects a file when restoring. Paw Agenda does not automatically upload backups. External copies remain at the destination chosen by the user, under that destination's terms and privacy practices.

## Document Archive

Users may select PDF, JPEG or PNG documents such as test results, prescriptions and vaccination records. Document content is stored inside the encrypted health record. A picker-owned temporary copy is removed after it is read; the original provider file is not deleted. When the user exports a document, a readable temporary copy is created for the share sheet and removed when the share flow returns. Archive-specific leftover temporary files are also cleaned at the next cold load and during a vault wipe.

Paw Agenda does not add password protection to exported archive files or automatically include their contents in veterinarian or sitter summaries. Deleting a pet profile can remove its documents or retain them under former profiles, according to the user's choice.

## Veterinarian Summaries

Summaries are generated locally from the selected pet's care journal, medication reminder history and health-passport records for the chosen period. Plain-text summaries are free; Plus also provides PDF summaries with measurement charts. They describe user-entered records and do not provide diagnosis or treatment recommendations. Archive file attachments are not automatically included.

The user reviews the included information and chooses whether and where to share through the system share sheet. Paw Agenda does not automatically send the report to the developer or a veterinarian. Exported text and PDF reports are not password-protected by Paw Agenda. Temporary report files are deleted when the sharing flow returns.

## Shareable Pet Cards

Cards are generated on the device from the selected pet's photo and name, a template and an optional caption. The preview shows the content that will be exported. Care records, health history and contact information are not automatically included. The user chooses whether and where to share the PNG image. Native temporary image files are released when the sharing flow returns.

## Sitter Handoff PDFs

Users can enter care instructions and contacts, and select individual health notes and active reminders for a sitter handoff. Form instructions and contacts are kept in memory while that screen is active and cleared when leaving the screen or changing the pet. They are not saved as a persistent draft or uploaded to a service.

The preview is free; sharing the locally generated PDF requires Plus. Photos, archive attachments and medication-administration history are not automatically included. The PDF is not password-protected and represents the information at the time it was created. It does not enable live collaboration or update a recipient's copy when the app's records change. Its temporary file is deleted when the sharing flow returns.

## Live Caregiver Sharing

A Plus owner may create an in-app routine list for one caregiver. Firebase Authentication creates an anonymous technical identifier without requesting an email address, phone number or social-login profile. Firebase/Google processes that identifier and the encrypted payload only to keep the live list available to the owner and accepted caregiver.

The payload is limited to the pet name and titles, categories, planned dates and planned times of the owner's current routine-care tasks. It is encrypted with AES-256-GCM in the app before upload. The encryption key is included in the owner-created invite link and is held in the owner and caregiver device secure storage; users should send it only to a trusted caregiver. Health-passport records, documents, photos, free-form notes, contacts, medication-administration history, local backups and local-vault keys are not included.

An invitation remains open for up to seven days and can be accepted by one caregiver. The caregiver can mark a shared task complete; completion appears in the live list and does not automatically write an entry to the owner's local Care Journal. The owner can revoke access at any time. Revocation prevents the caregiver from reading or updating the list under Firebase security rules and clears the device-held access key. The app does not run an automatic cloud-deletion job, so an encrypted, inaccessible record can remain in Firebase storage after revocation.

## Optional Firebase Analytics And Installation Measurement (iOS 1.2.0)

The general audience remains aged 9 and older. Analytics starts off, and its native Firebase service is not initialized until the user both declares they are 18 or older and gives separate explicit permission. No birth date is requested. Under-18 users, users who do not declare their age, and users who reject permission remain outside Analytics measurement. Declaring an adult age alone does not enable collection. Declining or withdrawing has no effect on pet records, Free functions or Plus access.

In Settings → Privacy → Optional measurement, the user first chooses an age group and then separately chooses whether to allow measurement. Nothing is preselected. The same screen offers rejection and, after permission, withdrawal. The choice is held in device-only Keychain storage with a matching installation marker. It is not transferred in a Paw Agenda backup; backup restoration and vault wiping reset it to off. Reinstallation requires a new choice. Storage/configuration errors leave collection off.

With permission, Firebase/Google receives an app-installation identifier, app version, device/operating-system characteristics, language, sessions and automatically recorded events such as the first app opening after installation or reinstallation. It may derive approximate location from network information and record supported in-app purchase events. This is used to understand app use and measure installation conversions through the existing Firebase/GA4 link to Google Ads. Consent to Analytics storage is granted only after the two choices. Advertising storage, advertising user-data sharing and advertising personalization consent remain denied. The iOS SDK excludes IDFA support; IDFV collection, automatic screen reporting and ad-personalization signals are disabled. The installation identifier still distinguishes an app installation; Analytics is not described as anonymous.

Pet names, photos, care and health records, free-form notes, documents, backups, invite secrets and local-vault keys are not supplied to Analytics events or user properties. The separate anonymous Firebase Authentication identifier used for caregiver sharing is not assigned as an Analytics user ID. Paw Agenda does not display ads or enable personalized-advertising audiences.

Withdrawal disables collection and Analytics/ad storage and resets the local Analytics identifier and state. It stops future app measurement; it does not automatically erase data previously received by Google. To request deletion of retained Analytics data, open Optional measurement → Analytics data deletion, copy the available installation identifiers, and email the privacy contact above with a deletion request. The developer can use those identifiers to request user-data deletion from Analytics. No email is sent automatically. Previously used identifiers are retained only on this device for this purpose, including after withdrawal; a vault wipe removes that local list. Make a deletion request before wiping or uninstalling if you need those identifiers. Without an identifier the developer may be unable to locate prior Analytics records. Exported copies and encrypted caregiver records follow their separate rules below.

The GA4 configuration checked on 30 September 2026 retains event data for two months and user data for fourteen months, with new activity resetting user-data retention. Aggregate reports can have different retention rules, and user-data deletion does not necessarily change historical aggregate reports. Google handles Analytics data according to its service terms and privacy policy, including processing outside the user's country where applicable.

The existing Google Ads link has personalized advertising disabled. The existing iOS first-open conversion is used; this update creates no second conversion. A direct test installation without an eligible ad interaction may appear in Analytics without increasing Ads' ad-attributed conversions. Advertising user-data consent is denied, so this policy does not promise individual-level ad attribution or an Ads count for each installation.

Services: [Google privacy policy](https://policies.google.com/privacy), [Firebase Analytics collection controls](https://firebase.google.com/docs/analytics/ios/configure-data-collection), and [Google Analytics data collection](https://support.google.com/analytics/answer/11593727?hl=en).

## Home Screen Widget

The free widget shortcut opens the care journal. An optional Plus count is off by default. If enabled, the date and total number of today's care entries for current pet profiles are copied outside the encrypted vault into on-device widget storage: an iOS App Group or private Android app preferences. Display labels, language information and an expiry time are also used to render the widget. The widget does not receive pet names, photos, notes, quantities, record identifiers or the vault key.

Enabling the app lock, turning the count off, restoring a backup or wiping the vault replaces the published count with a generic shortcut. The app also hides it when it determines that Plus is inactive. Tapping the widget uses the existing app unlock flow. Widget updates are controlled by the operating system, so a previously rendered image may remain visible until the system refreshes it. The count is dated and scheduled to return to a generic shortcut when the day changes. Paw Agenda does not upload widget snapshots or start remote widget notifications.

## Sharing, Retention And Deletion

Paw Agenda does not sell personal data or display advertisements. Optional adult Analytics and installation measurement are described above. Users can explicitly export encrypted backups, text/PDF summaries, pet cards and archive documents, or create the limited live caregiver share described above. The selected destination and any recipients control exported copies; deleting a record or wiping the app does not delete those copies.

Local records remain until the user deletes them or wipes the vault. A vault wipe removes encrypted records, the device-held vault key and reminder schedules, resets preferences, cleans archive temporary files and replaces the widget count with a generic shortcut. The operating system controls rendered widget images and app removal behavior. The app's normal export cleanup runs when the sharing flow returns; it cannot guarantee that cleanup completes if the process or device stops during an export. Temporary files may remain in the app's cache until cleaned or removed by the operating system.

Paw Agenda has no registered account system or developer-hosted readable pet-record database, so the developer cannot remotely identify or erase records on a user's device. A live-share owner can revoke the caregiver's access from the app. If a user emails the privacy contact, the developer receives the message and information the user chooses to include through that email service. Users should include only information needed for their request.

## App Updates And Error Reports

Application-code updates are distributed through the Apple App Store or Google Play. This release does not activate EAS Update or another remote-code update service. It has no app-owned error-reporting endpoint. Firebase Analytics in the next iOS binary is described above; existing published binaries do not gain that SDK from a server-side setting. Store purchase services and links opened by the user operate separately from local record storage. Operating-system and store diagnostics are governed by their respective platform settings and policies.

## Children And Families

Paw Agenda is intended for users aged 9 and older, including children, teenagers and adults. Children may use it for pet-care responsibilities with guidance from a parent or guardian. It does not create registered user accounts, display ads or provide free-form communication between users. Optional Plus purchases use the platform store. Parents and guardians should guide decisions about purchases and exporting photos, documents or contact details to other apps. They may contact the developer with privacy questions.

iOS 1.2.0 defaults Analytics collection to off. Collection is available only after an 18+ self-declaration and separate explicit permission. Under-18 and unknown-age users remain outside Analytics; parental permission does not unlock Analytics for under-18 users. Rejection and withdrawal remain available without loss of app features.

## Veterinary Guidance And Security

Paw Agenda is a recording and reminder tool, not a medical device. It does not provide veterinary diagnosis, treatment or emergency guidance. Users should consult a qualified veterinarian for medical decisions.

The app uses encryption for stored records, secure key storage, optional app locking, private notification text and password-protected backups. Readable exports and the widget cache are handled as described above. No system can guarantee absolute security.

## Changes To This Policy

Material changes to data handling will be reflected in an updated effective date and made available at the public policy URL before the relevant release. This includes any future account, general cloud-sync, analytics, advertising or developer-operated data-collection service.
