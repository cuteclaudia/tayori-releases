# Tayori (便り) privacy statement

*Last updated 29 October 2026. Tayori is CuteClaudia's mail, calendar, contacts and tasks program, part of the Kōbō suite.*

**In short:** Tayori has no account, no telemetry, no analytics, no advertising and no crash
reporting. Your files stay on your computer, or in storage you choose. CuteClaudia doesn't receive any
of your data.

## Your files

Tayori opens and saves files where you choose. It does not upload, copy or send them anywhere.
Settings and recent-file lists are kept in Tayori's settings folder on your computer.

## Your mail accounts

A mail program has to talk to your mail provider. Tayori connects **only to the servers of the accounts you add**, always encrypted (TLS):

- **Ordinary accounts (IMAP and SMTP)**: your provider's servers receive your sign-in and your mail, as with any mail program.
- **Outlook.com and Microsoft 365**: you sign in on Microsoft's own page in your browser; Tayori never sees your Microsoft password. It then reads and sends your mail, calendar, contacts and To Do tasks through Microsoft Graph, for you, under Microsoft's privacy terms. Microsoft shows you each permission before you agree.

Your mailbox (messages, calendar, contacts, tasks) is kept in files on your computer and on your provider's servers. Passwords and sign-in tokens are kept in memory, or, if you let Tayori remember them, in your computer's own credential store (Windows Credential Manager, GNOME Keyring or KWallet), never in Tayori's files or logs.

## Pictures inside email

Nothing in a message runs. Pictures that live on the web load **only when you ask** (for that message, or for senders you choose). Loading them tells the sender's web server your IP address and that the message was opened: that is why they stay off until you decide. Downloaded pictures are kept on your computer for up to 30 days and can be cleared in File › Options.

## What Tayori doesn't do

Unlike the program it is built on, Tayori never looks up mail servers through public DNS services (Cloudflare, Google) and never fetches sender pictures from Gravatar, favicon.im or Google. Report a Problem opens a page on GitHub in your browser; Tayori sends nothing itself.

## Updates

- **Copies from GitHub** (the installer or portable download): Tayori asks you once whether to check for new versions. If you agree, it asks GitHub's API at most once a day for the newest published release of `cuteclaudia/tayori-releases`. It's an ordinary web request, so GitHub sees your IP address and the usual request details, under GitHub's privacy statement. Tayori adds nothing about your accounts, your mail or the version you run.
- **Copies from the Microsoft Store**: the Store installs and updates Tayori; Tayori doesn't
  check GitHub at all. Microsoft's privacy statement covers the Store.

## Links

Links in Help and About (claudiagilbert.com, the releases page, feedback) open in your browser
**only when you click them**.

## Automation (optional)

Tayori can be controlled by scripts and AI agents through a control channel and an MCP server.
They are **off** unless you start them yourself, listen only on your own computer, and need a
secret key that only you have.

## Children

Tayori collects no personal information from anyone, including children.

## Changes and contact

Changes to this statement are published here, with the date at the top. Questions or concerns:
[open an issue](https://github.com/cuteclaudia/tayori-releases/issues/new) (please don't include
personal information or files), or contact CuteClaudia through claudiagilbert.com.
