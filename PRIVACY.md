# Privacy Policy — OpenBot Hermes (personal Google Workspace integration)

_Last updated: 2026-11-22_

## Who this applies to

This OAuth client is a **personal integration** used by a single individual
(`santosmitiel@gmail.com`) on a computer they own. There are no other users, no sign-up,
and no service offered to the public.

## What data is accessed

With the account owner's explicit consent, the local application may access:

- Gmail messages (read, search, send, modify labels)
- Google Calendar events (read, create, delete)
- Google Drive files (read, upload, download, create folders)
- Google Sheets (read and write cell ranges)
- Google Docs (read, create, append text)
- Google Contacts (read-only)

## How data is used and stored

- Data is used solely to answer the owner's own requests (for example: "summarize my
  unread e-mail", "create a calendar event").
- Data is **not** sold, shared, transferred, or disclosed to any third party.
- Data is **not** used for advertising, profiling, or training machine-learning models
  outside the owner's own agents.
- OAuth credentials (refresh token) and any cached content stay on the owner's computer,
  in the local Hermes/OpenBot profile directory. No server of ours stores them.
- Google user data is not transferred to others except as required by law.

## Retention and deletion

- Messages, files and events remain in the owner's Google account and are not duplicated
  elsewhere.
- The owner can revoke access at any time at
  <https://myaccount.google.com/permissions>, which immediately invalidates the stored
  refresh token and stops all access.
- Deleting the local token file
  (`google_token.json` in the Hermes profile directory) also removes the only local copy
  of the credential.

## Security

- Credentials are stored in a local file readable only by the owner's Windows account.
- All communication with Google uses HTTPS and the official Google APIs.

## Contact

santosmitiel@gmail.com
