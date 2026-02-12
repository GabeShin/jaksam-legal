# Jaksam Privacy Policy

**Effective Date**: February 12, 2026
**Last Updated**: February 12, 2026

---

## 1. Introduction

Jaksam ("the App") is a music lesson recording and practice management service for music students, teachers, and parents. This Privacy Policy describes the personal information the App collects, uses, stores, and shares.

By using the App, you agree to the practices described in this policy.

---

## 2. Information We Collect

### 2.1 Account Information

| Data | Required | Purpose |
|------|----------|---------|
| Email address | Yes | Account creation, login, password reset |
| Password | Yes | Authentication (stored encrypted) |
| Display name | Yes | Profile display within the App |
| Role (student/teacher/parent) | Yes | Role-based feature access |

### 2.2 Social Login

If you use Kakao Login, we receive the following from Kakao:
- Kakao account identifier
- Email address (if registered with your Kakao account)

### 2.3 User-Generated Content

| Data | Description |
|------|-------------|
| Lesson recordings (audio/video) | Music lessons recorded by the student |
| Practice recordings (audio/video) | Practice sessions recorded by the student |
| Profile photo | Optional profile image upload |
| Practice data | Practice duration, frequency, feedback responses |
| Learning goals | Student-set practice goals and deadlines |

### 2.4 Automatically Collected Information

| Data | Purpose |
|------|---------|
| Device push token | Sending push notifications |
| Error and crash data | App stability improvement (collected via Sentry) |
| App performance data | Service quality improvement |

Error reports may include device type, OS version, app version, and screen context at the time of the error. Recording content and personal messages are never included in error reports.

---

## 3. How We Use Your Information

We use collected information for the following purposes:

1. **Service delivery**: Account management, lesson/practice recording and playback, practice tracking
2. **AI features**: Audio transcription, lesson summary generation, practice plan generation, post-practice feedback question generation
3. **Notifications**: Push notifications for lesson processing completion, practice reminders
4. **Error monitoring**: Detecting app crashes and errors, improving service reliability
5. **Teacher/parent linking**: Connecting teachers and parents to students via invite codes for data sharing

---

## 4. Third-Party Services and Data Sharing

The App uses the following third-party services:

| Service Provider | Purpose | Data Shared |
|-----------------|---------|-------------|
| **Supabase** (US) | Authentication, database, file storage | Account info, recordings, all service data |
| **OpenAI** (US) | Audio transcription (Whisper API), summary/plan generation (GPT) | Recording audio, transcribed text |
| **Sentry** (US) | Error and performance monitoring | Error info, device info, user ID and role |
| **Kakao** (South Korea) | Social login (optional) | Authentication tokens |
| **Expo** (US) | Push notifications | Device push tokens |

### About OpenAI Data Processing

- Audio from lesson and practice recordings is sent to the OpenAI Whisper API for transcription.
- Transcribed text is sent to the OpenAI GPT API for summary and practice plan generation.
- Per OpenAI's API terms of service, data submitted via the API is not used for model training.

We do not sell your personal information to third parties.

---

## 5. Data Storage and Security

### 5.1 Retention

- Account information: Retained until account deletion
- Recordings and related data (transcripts, summaries, practice plans): Retained until deleted by the user or account deletion
- Error logs: 90 days from collection

### 5.2 Security Measures

- All data encrypted in transit via TLS/SSL
- Passwords stored with one-way hashing
- Database access restricted by row-level security (RLS) policies
- Recording file access restricted via signed URLs with expiration
- Server-side service keys are never exposed to the client

---

## 6. Your Rights

You have the following rights regarding your personal information:

1. **Access**: View your personal information in the App's settings.
2. **Correction**: Update your name, profile photo, and other profile information.
3. **Deletion of recordings**: Delete individual lesson and practice recordings.
4. **Account deletion**: Request account deletion, which permanently removes all personal information and recording data.
5. **Unlink**: Disconnect from linked teachers or parents at any time.

To request account deletion, use the in-app settings or contact us at the address below.

---

## 7. Teacher and Parent Data Access

- **Teachers**: Can view lesson recordings, transcripts, summaries, practice plans, and practice records of students linked via invite code. Teachers can modify practice plan items.
- **Parents**: Can view lesson and practice data of linked children (read-only).
- Linking is only possible through invite codes generated by the student, and students can unlink at any time.

---

## 8. Children's Privacy

The App does not intentionally collect personal information from children under 14 years of age. Users under 14 require parental consent to use the App. If we learn that personal information from a child under 14 has been collected without consent, we will promptly delete that information.

---

## 9. Changes to This Policy

If this policy is updated, we will notify you via in-app notice or email. For significant changes, we will provide at least 7 days' advance notice.

---

## 10. Contact Us

For questions about this Privacy Policy or your personal data, please contact us:

- **Email**: gabeshin.ts@gmail.com
- **App Name**: Jaksam

---

*This Privacy Policy complies with South Korea's Personal Information Protection Act (PIPA) and the requirements of the Apple App Store and Google Play Store.*
