# Octen Google access

This repository publishes the public information pages for the self-hosted Octen applications that connect to Google accounts.

- **Horizon** reads the calendars and events you choose to connect. Its Google access is read-only.
- **Mail Sifter** reads and organizes connected Gmail, sends messages when you choose to send them, and reads contacts to help fill recipient addresses. It also supports mail accounts connected through IMAP and SMTP.

Each application has its own OAuth client and asks for its own permissions. Connecting one application does not connect the other. Each Google account holder authorizes access separately and can revoke it in [Google Account settings](https://myaccount.google.com/connections).

The applications run on a privately hosted TrueNAS system. Their local databases hold connected-account tokens and the data needed by the applications. Google remains the provider of the original Gmail, Calendar, and Contacts data. This GitHub repository and its public pages contain only information about the applications; they do not receive connected-account data.

Read the [privacy policy](privacy.html) for the data each application uses, where it is stored, and how to revoke access. The [terms of use](terms.html) describe who may connect an account and how to get help. For questions about an account connected to a private installation, contact the person who operates that installation.

Public information site: [Octen Google access](https://google-access.octen.dev/).
Public information for Octen Google integrations
