---
title: Privacy Policy
permalink: /privacy/
---


Effective October 1, 2026

Central (previously called LocalSearch) is a Mac app made by Central ("we"). This policy explains what data the app and our connector
service handle. Questions or requests: dennischia1995@gmail.com.

## The short version

- Your files, mail, messages, index and searches stay on your Mac. We never receive them.
- The app sends no analytics or telemetry.
- If you connect Jira, our server keeps what it needs to keep you connected: your account email, your Atlassian
  account ID, the Jira sites you approved and an encrypted Jira access grant. It never sees your searches or your
  tickets.

## On your Mac

Central indexes the files and apps you choose and searches them on your Mac. The index is encrypted and stored
on your Mac. Model files are downloaded from their hosts and checked before use. None of this involves our servers.

## If you connect Jira

Connecting Jira is optional and requires a Central account.

**What our server stores**
- Your email address and sign-in details, held by our sign-in provider.
- A record for each Mac you sign in on: its name and when it was last used.
- Your Atlassian account ID and the list of Jira sites you approved.
- An encrypted refresh token from Atlassian, which lets your Mac get short-lived (up to one hour) access to Jira.

**What our server never receives**: your searches, Jira tickets, search results, files or anything else from your
Mac's index.

**Searching Jira**: your Mac sends what you type in the search box, and ticket keys you highlight (like
PROJ-123), directly to Atlassian. Other highlighted text is sent only when you press "Search Jira". These requests
go from your Mac to Atlassian, not through us. Atlassian's privacy policy covers what Atlassian does with them:
https://www.atlassian.com/legal/privacy-policy

**Jira permissions we ask for**: read-only access to Jira issues and projects (`read:jira-work`), basic user
profiles so tickets can show who they're assigned to (`read:jira-user`), and offline access so you don't have to
reconnect every hour. Central cannot create, change or delete anything in Jira.

## Server logs

Our server logs the time, route, result and your account ID for each request, to keep the service running and
secure. Logs never contain tokens, searches or Jira content.

## Sharing

We don't sell your data or use it for advertising. We use service providers to host our server, handle sign-in and
protect encryption keys; they process data only to run the service for us.

## Keeping and deleting data

- **Disconnect Jira** (Settings › Sources): we delete your Jira token and site list right away. Access your Macs
  already hold ends within an hour. To also remove Central on Atlassian's side, use your Atlassian account's
  connected apps page.
- **Sign out** of a Mac: we revoke that Mac's sign-in.
- **Delete your account** (Settings › Account): we delete your account and everything listed above.
- If you close your Atlassian account, we learn of it through Atlassian's reporting service (checked weekly) and
  delete your Jira data.

You can ask us at dennischia1995@gmail.com for a copy of your data, or to correct or delete it.

## Security

Jira refresh tokens are encrypted with keys kept outside our database. Your Mac keeps its sign-in in the macOS
Keychain and holds Jira access only in memory.

## Changes

If this policy changes, we'll post the new version here and update the date above.
