## Privacy Policy for PhotoTagger: Plus

Effective date: February 16, 2026

This Privacy Policy explains how PhotoTagger: Plus ("the App") handles information when you use the App.

## 1. Summary

- PhotoTagger: Plus is designed to work primarily on-device with your local photo library.
- We do not operate a backend service for media upload in the current app implementation.
- We do not use third-party analytics SDKs or advertising SDKs in the current app implementation.

## 2. Information the App Accesses

The App may access the following data on your device, with your permission:

- Camera data: to capture photos and videos.
- Microphone audio: to record audio in videos.
- Photo library/media files: to read, organize, rename, delete, and save photos/videos in albums managed by the App.
- In-app purchase status (iOS): to restore and validate premium entitlement through Apple services.

## 3. Information Stored Locally on Your Device

The App stores settings and app state locally, including:

- Filename preferences (such as separators).
- Saved tag memory values entered by you.
- Theme/app display preference.
- Premium flag/status for feature gating.
- App-managed album tracking metadata.

This local app data is stored via on-device storage mechanisms (for example, `SharedPreferences`).

## 4. Media Handling

- Captured photos/videos are saved to your device media library/albums (for example, app-related folders under your photo library/album structure).
- You can rename and delete media from within the App. On iOS, rename operations may involve delete-and-recreate behavior required by platform APIs.
- Sharing is initiated by you and performed through your device's native share sheet.

## 5. Network and Third Parties

Based on the current app code:

- No app-owned backend API endpoints are used for uploading your media.
- No advertising network SDK is integrated.
- No analytics/crash-reporting SDK (such as Firebase Analytics/Crashlytics) is integrated.

Platform services may still process data as needed to provide system functionality:

- Apple App Store services for purchase/restore flows on iOS.
- OS-level media and permission frameworks on Android and iOS.

## 6. Permissions

The App requests permissions necessary for core features:

- Camera
- Microphone (video recording)
- Photo/media library access (read and add/save)

If you deny permissions, parts of the App may not function.

## 7. Children's Privacy

The App is not directed to children under 13, and we do not knowingly collect personal information directly from children through an app backend.

## 8. Data Retention and Deletion

- Local settings persist on your device until removed.
- Media files remain in your device photo library unless you delete them (inside the App or directly on your device).
- You can remove the App from your device to delete app-local settings, subject to OS behavior and backups.

## 9. International Use

Because data handling is primarily local/on-device in the current implementation, cross-border transfer by us is generally limited. Your platform provider (for example Apple/Google) may process data under their own terms.

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. Updated versions will be posted with a new effective date.

## 11. Applicable Privacy Framework

This Privacy Policy is intended to align with applicable data protection laws in Germany and the European Union, including the GDPR where applicable.

## 12. Contact

For privacy questions, contact:

- Email: contact@example.com

If your production contact details differ, replace this address before publishing.
