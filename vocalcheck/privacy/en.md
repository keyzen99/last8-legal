---
layout: default
title: Privacy Policy
permalink: /vocalcheck/privacy/en/
---

[Privacy Policy / プライバシーポリシー](./)

# Privacy Policy (VocalCheck)

Last updated: 2026-04-10

## 1. Overview
VocalCheck (the "App") is an AI-powered vocal training coach. We respect your privacy and are transparent about the data we handle.

## 2. Information We Collect

### Account Information
The App uses Firebase Authentication for sign-in. When you sign in with Google, Apple, or email, we receive your display name and email address solely for authentication purposes.

### Audio Data
The App uses your device's microphone to detect pitch in real time during vocal exercises. Audio is processed locally on your device and is not sent to external servers. Recordings you save are stored only on your device.

### Vocal Goal Input
When you set a vocal goal (e.g., "I want to sing like Bruno Mars"), your text input is sent to Google's Gemini AI service for analysis. The AI response (training weights and advice) is stored locally on your device. Google may process this data under their own privacy policy.

### Training Data
Exercise scores, session history, streaks, and progress data are stored locally on your device using an on-device database.

## 3. Information Stored on Your Device
- Voice range (lowest/highest pitch detected)
- Training level and exercise history
- Session scores (pitch, stability, rhythm)
- Vocal goal analysis results
- Subscription status

This data stays on your device and is not sent to any developer server.

## 4. Network Access
The App connects to the internet for:
- **Authentication**: Firebase Authentication (sign-in/sign-out)
- **AI Analysis**: Google Gemini API via Firebase AI (vocal goal analysis only)
- **Purchases**: Apple App Store / Google Play for subscription management

The App does not perform background network communication.

## 5. Sharing with Third Parties
We do not sell or share your personal data with third parties. Data is shared only with:
- **Firebase (Google)**: For authentication and AI analysis
- **Apple / Google**: For in-app purchase processing

## 6. Third-Party SDKs
- **Firebase Auth**: User authentication
- **Firebase AI (Gemini)**: Vocal goal text analysis
- **In-App Purchase**: Subscription management via platform stores

The App does not use advertising SDKs, analytics SDKs, or tracking SDKs.

## 7. Purchases
Subscription payments (Pro plan) are processed by Apple/Google platforms. We do not receive or store your payment card information.

## 8. Microphone Permission
The App requests microphone access (`RECORD_AUDIO`) for real-time pitch detection during vocal exercises. Audio is processed on-device only. You can revoke this permission at any time in your device settings.

## 9. Children's Privacy
The App is not directed at children under 13. We do not knowingly collect personal information from children.

## 10. Data Deletion
You can delete all local data by uninstalling the App. To delete your Firebase account, use the sign-out and account deletion option in the App's profile screen.

## 11. Changes
We may update this policy to reflect changes in the App or legal requirements. Updates will be posted on this page.

## 12. Contact
For questions about this policy, please contact us via the repository Issues page:
- https://github.com/keyzen99/VocalCheck-Flutter/issues
