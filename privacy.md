# Privacy Policy for Auto BGM Personal

**Last updated:** 2026-05-26

## Overview

Auto BGM Personal ("the App") is a personal automation tool developed and used by a single individual (the developer) to upload AI-generated background music videos to the developer's own YouTube channel. This application is **not offered to or used by any other person, organization, or third party**.

## Who Uses This App

- **Sole user:** The developer (the creator of this repository) only.
- This app is **not** distributed, sold, or made available to anyone else.
- No login or sign-up is provided for external users — the app uses the developer's own Google account exclusively.

## Data Access

The App requests the following Google OAuth scope:
- `https://www.googleapis.com/auth/youtube` — to upload videos, set thumbnails, and manage metadata on the developer's own YouTube channel.

### What data is accessed
- Video uploads (video files, titles, descriptions, tags, thumbnails) **created locally by the developer**.
- Channel information needed to perform uploads (channel ID, upload status).

### What data is NOT accessed
- The App does **not** read, modify, or share other users' content.
- The App does **not** access viewer comments, subscriber lists, analytics, or financial data.
- The App does **not** access any Google account other than the developer's own.

## Data Storage

- OAuth tokens (`token.json`) are stored **locally** on the developer's personal computer and on the developer's private EC2 instance.
- No data is transmitted to any third-party server.
- No data is sold, shared, or used for advertising.
- Generated video files, thumbnails, and metadata are stored locally on the developer's machine and are deleted after successful upload.

## Data Retention

- OAuth refresh tokens are retained until manually revoked by the developer.
- The developer can revoke access at any time via https://myaccount.google.com/permissions.

## Third Parties

The App does not share any data with any third party. The App communicates only with:
- Google's YouTube Data API v3 (for the developer's own channel uploads only).

## Compliance

The App's use of information received from Google APIs adheres to Google's [Limited Use requirements](https://developers.google.com/terms/api-services-user-data-policy#limited-use) and the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy).

## Children's Privacy

The App is not directed to children under 13. The App does not knowingly collect any data from children.

## Changes to This Policy

Any changes will be reflected in this document with an updated "Last updated" date.

## Contact

For questions about this privacy policy, contact the developer at the email address registered with this OAuth application in Google Cloud Console.
