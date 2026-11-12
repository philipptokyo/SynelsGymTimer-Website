# Privacy Policy for SynelsGymTimer

**Last updated:** 2026-11-12

## 1. Developer and Contact

SynelsGymTimer is provided by:

Philipp Schrock  
Germany  
Email: Philipp.Schrock@iCloud.com

This policy explains the handling of personal information in connection with the iPhone and Apple Watch apps, beta testing, support enquiries and this website.

## 2. Overview

SynelsGymTimer is a workout interval timer. It is currently provided as a free hobby project and does not require an account or registration.

The app contains no advertisements, advertising SDKs or third-party analytics SDKs.

Workout settings and health records are not uploaded to servers operated by the developer. The developer cannot access those records through the app's normal workout functions.

Additional information is processed when the Watch app downloads this policy, when you visit the website, when you use Apple TestFlight or when you contact the developer.

## 3. Settings Stored on Your Devices

The app stores workout settings locally, including:

- Countdown duration
- Number of exercises and sets
- Exercise duration
- Rest duration
- Transition duration between exercises

It also stores technical information for exchanging settings between iPhone and Apple Watch. This includes randomly generated identifiers, revision numbers, pending transfers and delivery acknowledgements.

These details allow the app to identify transfers, confirm delivery and avoid applying outdated settings. They are not used for advertising or tracking.

Local settings remain until they are overwritten or the corresponding app data is removed. Removing the app from one device does not automatically remove settings from another device.

Device backups and restoration depend on your Apple settings.

## 4. Sending Settings Between Devices

When you use the app's send function, workout settings are transferred between your iPhone and Apple Watch using Apple's WatchConnectivity framework.

A pending transfer may be delivered later if the receiving device is temporarily unavailable. Technical identifiers and acknowledgements are exchanged to manage delivery.

Health records are not included in this settings transfer.

Both apps can be used independently. The companion app is optional.

## 5. Apple Health and HealthKit

The Watch app uses HealthKit to start, manage and save strength training sessions. An active workout session also supports operation of the timer in the background.

The app requests permission to save workouts to Apple Health. It does not request permission to read previously stored health records. Without the required permission, a workout cannot be started in the Watch app. The iPhone timer does not require HealthKit access.

When a workout finishes or is ended using the app's end button, the app attempts to save it to Apple Health. Force-quitting the app or a technical interruption may prevent saving.

The workout record includes its type, start time, end time and duration.

During an active session, Apple Watch and HealthKit may also automatically record associated measurements, such as heart rate or energy expenditure, depending on the workout configuration, available sensors and system settings. SynelsGymTimer does not display or separately analyse these measurements.

Pausing the timer does not pause the underlying HealthKit session. The saved workout duration can therefore include time spent with the timer paused.

These health records are not transmitted to the developer through the app's workout or settings-transfer functions.

You can change HealthKit permissions in your Apple devices' Health or privacy settings. Revoking permission does not automatically delete previously saved workouts. You can delete those records using Apple's Health tools. Uninstalling SynelsGymTimer does not automatically remove them.

Any synchronisation of health records through Apple services depends on your Apple settings.

Further information:

[Apple: Running Workout Sessions](https://developer.apple.com/documentation/healthkit/running-workout-sessions)  
[Apple Privacy Policy](https://www.apple.com/legal/privacy/)

## 6. Notifications and Sounds

With your permission, the iPhone app schedules local notifications for workout phase changes.

They are scheduled on the device and do not require a push notification server operated by the developer. They are not used for advertising.

You can change notification permissions and sound settings in your iPhone settings.

## 7. Accessing This Privacy Policy

### Website and Watch Downloads

The website is hosted through GitHub Pages. The Watch app downloads the policy's Markdown source from the same public GitHub repository through raw.githubusercontent.com.

The Watch checks for an update when you open its privacy screen or select Refresh or Retry. It does not periodically download the policy during workouts.

These requests disclose technical connection information to GitHub, including your IP address. GitHub states that it logs and stores GitHub Pages visitors' IP addresses for security purposes.

The Watch's download request does not include your workout settings, health records or settings-transfer identifiers.

The purpose is to provide accessible, current privacy information. Where the GDPR applies, the developer relies on Article 6(1)(f), with the legitimate interest of providing that information reliably.

Further information:

[GitHub Pages: Data Collection](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection)  
[GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)

### Offline Storage

The Watch stores the last successfully downloaded policy and its download date locally. This copy remains readable offline and is replaced after a successful update. Failed downloads do not replace it.

“Downloaded” indicates when the copy was retrieved. The “Last updated” date within the policy identifies its stated revision date.

The copy remains until it is replaced or the corresponding app data is removed. Backups depend on your Apple settings. Offline storage serves the legitimate interest of keeping privacy information accessible without a connection under Article 6(1)(f) GDPR, where applicable.

### View on iPhone

Selecting View on iPhone offers the public policy address and title through Apple's Handoff feature while the Watch privacy screen remains open.

A compatible nearby device may then offer to continue in a browser. The app does not automatically open the browser or confirm receipt on another device.

No health records or workout settings are included in this activity. Availability depends on your devices and Apple settings.

## 8. Apple TestFlight

When you use the beta through TestFlight, Apple automatically collects crash logs and usage information and shares them with the developer. This cannot be disabled while using TestFlight.

Information may include device and operating system details, app versions, installations, sessions and crashes. Feedback you submit, including comments and screenshots, is also shared.

Names and email addresses may be available depending on the invitation method. When you join exclusively through a public link, Apple does not display your name or email address in the tester information. You can still disclose identifying details in feedback.

The developer uses this information to investigate problems and improve the app. The legal basis is Article 6(1)(f) GDPR: the legitimate interest in evaluating and improving the beta.

Apple manages retention within its services. Apple states that feedback is retained for one year and crash logs and usage data may be retained until bugs are resolved.

Please remove health information and other confidential details from screenshots or feedback before submission.

[TestFlight & Privacy](https://www.apple.com/legal/privacy/data/en/test-flight/)

## 9. Support and Retention

If you contact the developer, your email address, message and attachments are processed to respond to your enquiry.

The developer uses Apple iCloud Mail for email correspondence. Messages are received and stored through that service.

The developer personally handles support and TestFlight feedback and does not forward it to other people or external analysis services. Apple processes information as part of providing iCloud Mail and TestFlight.

Support processing is based on Article 6(1)(f) GDPR. The legitimate interest is to respond to enquiries and investigate reported problems.

Support correspondence and any separately saved feedback or diagnostic reports are retained for as long as necessary to respond to the enquiry or investigate and resolve the reported issue. Once no longer needed for these purposes, they are deleted unless legal obligations require continued retention.

Please avoid sending health records or other sensitive personal information.

[Apple Privacy Policy](https://www.apple.com/legal/privacy/)

## 10. Service Providers and International Processing

The services described above involve:

- **Apple**, for HealthKit and Apple Health, TestFlight, iCloud Mail, Handoff and any device backup or synchronisation you enable.
- **GitHub**, for delivering the website and the policy source downloaded by the Watch.

These are distinct services. Using one does not mean that health records are sent through the others.

Apple and GitHub describe processing outside the European Economic Area, including in the United States.

Apple's privacy policy describes Standard Contractual Clauses for relevant international transfers. GitHub's privacy statement describes Standard Contractual Clauses and participation in the Data Privacy Framework for covered transfers. Details, scope and contact information are available in their policies:

[Apple: International Processing](https://www.apple.com/legal/privacy/en-ww/)  
[GitHub: International Data Transfers](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement#international-data-transfers)

## 11. Your Rights and Choices

Where applicable under data protection law, you may request access, correction, deletion, restriction of processing or data portability.

You may object, on grounds relating to your particular situation, to processing based on legitimate interests. Where processing relies on consent, you may withdraw that consent with effect for the future.

You may also lodge a complaint with a competent supervisory authority, including in the country of your habitual residence, workplace or an alleged infringement.

For requests concerning information held by the developer, contact Philipp.Schrock@iCloud.com.

The developer cannot directly retrieve or delete settings and health records stored exclusively on your devices or in Apple Health. Manage those records and permissions through your Apple devices.

The app requires no registration or contact details for its workout functions. Submitting feedback and contacting the developer are voluntary. HealthKit permission is required for Watch workouts; notification permission is required for iPhone notifications.

The developer does not use personal information for automated decision-making or profiling within the meaning of Article 22 GDPR.

[General Data Protection Regulation](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32016R0679)

## 12. Changes

This policy may be updated when the app or its data-handling practices change. The current version is available on this website.

The Watch downloads the same maintained source. It does not contain a policy permanently bundled with an app release. An offline copy may be older than the online version; the Watch shows when it was downloaded and indicates an unsuccessful refresh.
