---
layout: default
title: Privacy Policy - Jaksam
---

# Jaksam Privacy Policy

**Effective Date**: February 12, 2026
**Last Updated**: March 5, 2026

---

## 1. Introduction

Jaksam ("the App") is a music lesson recording and practice management service for music students, teachers, and parents. This Privacy Policy describes the personal information the App collects, uses, stores, and shares.

By using the App, you agree to the practices described in this policy.

---

## 2. Consent to AI Data Processing

The App uses artificial intelligence (AI) technology to provide its core features. **When you first use the App, you will be asked for explicit consent to AI data processing. The service cannot be used without this consent.**

Data involved in AI processing includes:
- Audio/video from lesson and practice recordings (for transcription)
- Transcribed text (for generating summaries, practice plans, and feedback questions)
- Student profile information (for personalized AI coaching)
- Practice records and feedback responses (for generating tailored advice)
- Conversations with the AI coach (for maintaining conversation context and generating responses)

This data is processed through **OpenAI**'s API, located in the United States. Per OpenAI's API terms of service, data submitted via the API is not used for model training.

You may withdraw your consent at any time through the App's settings. Withdrawing consent will disable AI features.

---

## 3. Information We Collect

### 3.1 Account Information

| Data | Required | Purpose |
|------|----------|---------|
| Email address | Yes | Account creation, login, password reset |
| Password | Yes | Authentication (stored encrypted) |
| Display name | Yes | Profile display within the App |
| Role (student/teacher/parent) | Yes | Role-based feature access |

### 3.2 Social Login

If you use Kakao or Apple login, we receive the following from the respective service:
- Account identifier
- Email address (if registered with the account)

### 3.3 Student Profile Information

Students may optionally provide the following during onboarding or in settings:

| Data | Purpose |
|------|---------|
| Date of birth | Age-appropriate AI coaching |
| Instrument type | Instrument-specific practice plan generation |
| Years of playing experience | Level-appropriate feedback |
| Daily/weekly practice goals | Practice progress tracking and reminders |
| Preferred practice time | Notification timing optimization |

This information is used by the AI to generate personalized feedback and practice plans appropriate for the student's level.

### 3.4 User-Generated Content

| Data | Description |
|------|-------------|
| Lesson recordings (audio/video) | Music lessons recorded by the student |
| Practice recordings (audio/video) | Practice sessions recorded by the student |
| Profile photo | Optional profile image upload |
| Practice data | Practice duration, frequency, feedback responses |
| Learning goals | Student-set practice goals and deadlines |
| Feedback responses | Student responses to post-practice and check-in questions |
| AI coach conversations | Chat messages with the AI coach (Jaksam) |

### 3.5 Automatically Collected Information

| Data | Purpose |
|------|---------|
| Device push token | Sending push notifications |
| Error and crash data | App stability improvement (collected via Sentry) |
| App performance data | Service quality improvement |

Error reports may include device type, OS version, app version, and screen context at the time of the error. Recording content and personal messages are never included in error reports.

---

## 4. How We Use Your Information

We use collected information for the following purposes:

1. **Service delivery**: Account management, lesson/practice recording and playback, practice tracking
2. **AI transcription**: Converting recorded audio/video to text (OpenAI Whisper API)
3. **AI summary and plan generation**: Lesson summaries, practice plans, and feedback question generation (OpenAI GPT API)
4. **AI coaching**: Personalized practice advice, daily practice plans, and weekly check-in messages (OpenAI GPT API)
5. **Notifications**: Push notifications for lesson processing, practice reminders, and AI coaching messages
6. **Error monitoring**: Detecting app crashes and errors, improving service reliability
7. **Teacher/parent linking**: Connecting teachers and parents to students via invite codes for data sharing

---

## 5. Third-Party Services and Data Sharing

The App uses the following third-party services:

| Service Provider | Purpose | Data Shared |
|-----------------|---------|-------------|
| **Supabase** (US) | Authentication, database, file storage | Account info, recordings, all service data |
| **OpenAI** (US) | Audio transcription (Whisper API), summary/plan/coaching generation (GPT API) | Recording audio, transcribed text, student profile, feedback responses, AI coach conversations |
| **Sentry** (US) | Error and performance monitoring | Error info, device info, user ID and role |
| **Kakao** (South Korea) | Social login (optional) | Authentication tokens |
| **Apple** (US) | Apple Sign In (optional) | Authentication tokens |
| **Expo** (US) | Push notifications | Device push tokens |

### About OpenAI Data Processing

The following data is sent to OpenAI's API:

- **Transcription**: Audio from lesson and practice recordings is sent to the OpenAI Whisper API for text conversion.
- **Summary/plan generation**: Transcribed text is sent to the OpenAI GPT API for generating summaries and practice plans.
- **AI coaching**: Student profile data (age, instrument, experience level), recent practice records, feedback responses, and prior conversation history are sent to the OpenAI GPT API for generating personalized coaching messages.
- **Weekly check-in**: Weekly practice data and lesson summaries are sent to the OpenAI GPT API for generating check-in questions.

Per OpenAI's API terms of service, data submitted via the API is not used for model training.

We do not sell your personal information to third parties.

---

## 6. Data Storage and Security

### 6.1 Retention

- Account information: Retained until account deletion
- Recordings and related data (transcripts, summaries, practice plans): Retained until deleted by the user or account deletion
- AI coach conversation history: Retained until deleted by the user or account deletion
- Error logs: 90 days from collection

### 6.2 Security Measures

- All data encrypted in transit via TLS/SSL
- Passwords stored with one-way hashing
- Database access restricted by row-level security (RLS) policies
- Recording file access restricted via signed URLs with expiration
- Server-side service keys are never exposed to the client

---

## 7. Your Rights

You have the following rights regarding your personal information:

1. **Access**: View your personal information in the App's settings.
2. **Correction**: Update your name, profile photo, and other profile information.
3. **Deletion of recordings**: Delete individual lesson and practice recordings.
4. **Account deletion**: Request account deletion through the App's settings. A 30-day grace period applies after the request. If you log in during the grace period, the deletion is canceled. After the grace period, all personal information and recording data are permanently deleted.
5. **Unlink**: Disconnect from linked teachers or parents at any time.
6. **Withdraw AI consent**: Withdraw your consent to AI data processing at any time.

To request account deletion, go to Settings > Edit Profile > Delete Account in the App, or contact us at the address below.

---

## 8. Teacher and Parent Data Access

- **Teachers**: Can view lesson recordings, transcripts, summaries, practice plans, and practice records of students linked via invite code. Teachers can modify practice plan items.
- **Parents**: Can view lesson and practice data of linked children (read-only).
- Linking is only possible through invite codes generated by the student, and students can unlink at any time.

---

## 9. Children's Privacy

The App does not intentionally collect personal information from children under 14 years of age. Users under 14 require parental consent to use the App. If we learn that personal information from a child under 14 has been collected without consent, we will promptly delete that information.

---

## 10. Changes to This Policy

If this policy is updated, we will notify you via in-app notice or email. For significant changes, we will provide at least 7 days' advance notice.

---

## 11. Contact Us

For questions about this Privacy Policy or your personal data, please contact us:

- **Email**: gabeshin.ts@gmail.com
- **App Name**: Jaksam

---

*This Privacy Policy complies with South Korea's Personal Information Protection Act (PIPA) and the requirements of the Apple App Store and Google Play Store.*
