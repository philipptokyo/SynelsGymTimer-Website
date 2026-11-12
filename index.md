# Privacy Policy for SynelsGymTimer

**Last updated:** 2026-11-12  
**Status:** Draft for pre-release testing. Legal review is pending.

## 1. Data Controller and Contact

The person responsible for data processing in connection with SynelsGymTimer is:

Philipp Schrock  
Email: Philipp.Schrock@iCloud.com

This Privacy Policy explains how personal data is processed when using SynelsGymTimer for iPhone and Apple Watch, when participating in beta testing, and when visiting this website.

## 2. Overview

SynelsGymTimer is a workout interval timer for iPhone and Apple Watch. It does not require an account or registration.

The app does not contain advertisements, advertising SDKs, or third-party analytics SDKs.

Workout settings and health data are not transmitted to servers operated by the developer. The developer does not have access to your health data through the app's normal workout functions.

Additional information may be processed through Apple TestFlight, when you contact the developer, or when you visit this website, as described below.

## 3. Workout Settings and Local Storage

SynelsGymTimer stores workout settings locally on each device. These include:

- Initial countdown duration
- Number of exercises and sets
- Exercise duration
- Rest duration
- Transition duration between exercises

The app also stores technical information used to exchange settings between iPhone and Apple Watch. This includes randomly generated identifiers, revision numbers, pending transfers, and delivery acknowledgements.

These details help identify transfers, confirm delivery, and prevent outdated settings from being applied again. They are not used for advertising or tracking.

Processing serves to provide the app functionality you request. Where applicable, the legal basis is Article 6(1)(b) GDPR.

Local data remains stored until it is overwritten or the corresponding app data is removed. Removing the app from one device does not automatically remove settings stored on another device.

Device backups and restoration are governed additionally by your Apple device and iCloud settings.

## 4. Communication Between iPhone and Apple Watch

When you use the app's send function, SynelsGymTimer transfers workout settings between your iPhone and Apple Watch using Apple's WatchConnectivity framework.

If the receiving device is temporarily unavailable, a pending transfer may be delivered later when communication becomes possible.

The technical identifiers and acknowledgements described in Section 3 may also be exchanged to identify transfers and confirm delivery.

Health data and recorded workout sessions are not transferred through this settings synchronization feature.

Processing serves to perform the transfer you request. Where applicable, the legal basis is Article 6(1)(b) GDPR.

Both apps can be used independently. Installing the companion app is optional.

## 5. Apple Health and HealthKit

The Apple Watch app uses Apple's HealthKit framework to start, manage, and save strength training sessions.

An active HealthKit workout session also supports the workout timer's operation while the Watch app is in the background.

The Watch app requests permission to save workout records to Apple Health. It does not request permission to read previously stored health data.

Without the required HealthKit authorization, a workout cannot be started in the Watch app. The iPhone timer works independently and does not require HealthKit authorization.

After a workout finishes or is ended using the app's end button, the app attempts to save the workout to Apple Health. Force-quitting the app or a technical interruption may prevent the workout from being saved.

The workout record includes information such as:

- Workout type
- Start time
- End time
- Workout duration

Pausing the timer does not pause the underlying HealthKit workout session. Consequently, the saved workout duration can include time spent with the timer paused.

Health data is not sent to the developer or used for advertising.

### Legal basis — pending confirmation

The legal basis for processing health data must be confirmed before this draft is finalized. If explicit consent is used, the relevant provisions are Article 6(1)(a) and Article 9(2)(a) GDPR.

Apple's HealthKit permission interface provides technical authorization. This draft does not assume that technical authorization alone necessarily satisfies the requirements for explicit consent under the GDPR.

### Managing permissions and saved workouts

You can revoke HealthKit authorization through the Health or privacy settings on your Apple devices.

Revoking authorization affects future access. It does not automatically delete workout records already saved to Apple Health.

Saved workouts can be deleted using Apple's Health tools. Uninstalling SynelsGymTimer does not automatically delete those records.

Synchronization through Apple Health, other Apple devices, or iCloud depends on your Apple settings and is governed additionally by Apple's privacy information:

[Apple Privacy Policy](https://www.apple.com/legal/privacy/)

## 6. Notifications and Sounds

With your permission, the iPhone app schedules local notifications to announce workout phase changes.

These notifications are scheduled on your device. They do not require a push notification server operated by the developer.

You can change notification permissions and sound settings in your iPhone settings.

Notifications are not used for advertising or tracking.

## 7. Beta Testing Through Apple TestFlight

When you use SynelsGymTimer through Apple TestFlight, Apple automatically collects crash logs and usage information and shares them with the developer. This collection cannot be disabled while using TestFlight.

Feedback you choose to submit through TestFlight is also shared with Apple and the developer.

Information made available through TestFlight may include:

- Crash logs and diagnostic information
- Device model and a device identifier
- Operating system and app versions
- Installation, session, and crash information
- Testing invitation status
- Feedback comments
- Screenshots and other information you submit
- Your name and email address, depending on the invitation method and feedback provided

If you join exclusively through a public invitation link, Apple does not display your name or email address to the developer as part of the tester information. You may still disclose identifying information yourself in feedback or screenshots.

The developer uses beta testing information to investigate problems, respond to feedback, and improve the app's functionality and stability.

The legal basis is Article 6(1)(f) GDPR. The legitimate interest is to evaluate the beta version and identify and resolve technical problems.

Feedback and diagnostic information stored separately by the developer is deleted when no longer needed for these purposes, unless legal retention obligations apply.

Apple manages retention within its own services. Apple states that beta app feedback is retained for one year and that crash logs and usage data may be retained until bugs are resolved.

Please avoid including health data or other confidential information in feedback or screenshots. If necessary, redact those details before submitting feedback.

For further information:

[TestFlight & Privacy](https://www.apple.com/legal/privacy/data/en/test-flight/)

## 8. Contacting the Developer

If you contact the developer by email, your email address, message content, and any attachments are processed to respond to your inquiry.

Messages are handled using the developer's email service, Apple iCloud Mail.

For inquiries necessary to provide the app's requested functionality, the legal basis is Article 6(1)(b) GDPR, where applicable. For other inquiries, the legal basis is Article 6(1)(f) GDPR. The legitimate interest is to respond to messages and provide support.

Correspondence is retained only as long as needed to handle the inquiry and necessary follow-up, unless legal retention obligations require longer storage.

Please do not send health data or other sensitive information unless it is necessary for your inquiry.

## 9. Website Hosting Through GitHub Pages

This website is hosted through GitHub Pages, a service provided by GitHub, Inc., United States.

When you access the website, GitHub processes technical connection information to deliver the page and maintain the security of its service. GitHub states that visitors' IP addresses are logged and stored for security purposes.

The legal basis for providing this website is Article 6(1)(f) GDPR. The legitimate interest is to make information about SynelsGymTimer and its privacy practices available reliably and securely.

The developer does not add advertising services, analytics tools, tracking pixels, or third-party font services to this website.

GitHub may process information outside the European Economic Area, including in the United States. Details about GitHub's processing, retention, and international transfer safeguards are available in its privacy statement:

[GitHub General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)

## 10. Recipients and International Processing

Depending on the features and services used, information may be processed by:

- **Apple**, in connection with HealthKit, device services, backups, TestFlight, and email communication
- **GitHub**, when you access this website
- **The developer**, when reviewing TestFlight information or responding to messages

The developer does not receive health data through the app's normal workout functions and does not sell personal data or share it for advertising.

Apple and GitHub may process information outside the European Economic Area. Their respective privacy information describes their international processing and transfer safeguards.

**Draft item to resolve before finalization:** Confirm the applicable service providers, their roles, and the specific international transfer arrangements relevant to this app, website, and support email.

## 11. Your Data Protection Rights

Subject to applicable legal requirements, you have the right to:

- Access your personal data
- Have inaccurate personal data corrected
- Request deletion of personal data
- Request restriction of processing
- Receive personal data in a portable format, where applicable
- Withdraw consent with effect for the future, without affecting the lawfulness of processing before withdrawal

Where processing is based on Article 6(1)(f) GDPR, you may object on grounds relating to your particular situation.

You also have the right to lodge a complaint with a competent data protection supervisory authority, particularly in the country of your habitual residence, place of work, or the alleged infringement.

For requests concerning processing by the developer, use the email address in Section 1.

The developer cannot directly access or delete settings and health records stored exclusively on your devices or in Apple Health. You can manage those records and their permissions through your Apple devices and services.

## 12. Automated Decision-Making

The developer does not use personal data for automated decision-making or profiling within the meaning of Article 22 GDPR.

## 13. Providing Data and Permissions

SynelsGymTimer does not require registration or submission of contact information to use its normal workout functions.

Local processing of workout settings is necessary to provide the timer functions. HealthKit authorization is required to start a workout in the Apple Watch app.

Contacting the developer and submitting feedback are voluntary. Participation in TestFlight is also voluntary, but the automatic diagnostic and usage data collection described in Section 7 is part of using that service.

## 14. Changes to This Privacy Policy

This Privacy Policy may be updated when the app's functionality, data processing, or supporting services change.

The latest version is available on this website. A copy included in the Watch app reflects the version supplied with that app release.
