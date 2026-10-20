# Privacy Policy

**Postern for macOS** · Effective 20 October 2026

Postern connects to file servers that you choose and shows them in Finder. This
policy explains what happens to information when you use the app, its Finder
extension, and this website.

In short: the app keeps your connections and credentials on your Mac and sends
them only to the servers you configure. We do not collect, see, sell, or share
them.

## Who we are

Postern is developed and published by Ryan McFadden ("we", "us"). For privacy
questions, contact **support@honestlymylove.com**.

## What Postern stores on your Mac

Postern keeps everything it needs locally, in your macOS Keychain:

- Connection details you enter: display name, protocol, server address, port,
  username, and optional starting directory.
- Authentication secrets: passwords or SSH private keys.
- SSH host keys you have reviewed and approved.
- Loopback relay endpoints used while a connection is active.

These items use Keychain services whose names begin with
`com.honestlymylove.isftp`, and they are accessible only to Postern and its
Finder extension. They are protected by your macOS account and Keychain. We
cannot read them.

Postern does not create an account and does not store your information on any
server that we operate.

## What leaves your Mac

When you open or use a connection, Postern connects directly to the server you
configured, using the protocol you selected: SFTP, FTP, FTPS, WebDAV, or
WebDAVS. Your credentials are sent to that server as part of its normal
authentication, and the server operator's privacy practices apply to that
exchange.

We do not receive a copy of your files, credentials, server addresses, or usage.
There is no Postern account, cloud service, or telemetry endpoint.

FTP sends credentials and data unencrypted. Prefer SFTP, FTPS, or WebDAVS on
networks you do not control.

## Purchases

Postern Full is a one-time in-app purchase processed by Apple. Apple handles
payment and may provide us with anonymised sales and entitlement information. We
never receive your payment details. Apple's handling of your information is
governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## Diagnostics

Postern does not include analytics, advertising, or third-party tracking SDKs.
macOS and the App Store may collect crash reports and usage diagnostics
according to your system settings. That collection is controlled by Apple and
your preferences, not by us.

## This website

Our web host may record standard server logs (such as IP address, user agent,
requested page, and time) when you visit this site. We use them only to operate
and secure the site. We do not use advertising or analytics cookies, and we do
not build profiles of visitors.

## Sharing and selling

We do not sell, rent, or share personal information. We hold no user database to
share.

## Retention and deletion

Connection details and credentials remain on your Mac until you delete the
connection, which also removes its stored secret, or until you remove the app and
its Keychain items. To remove items manually, open **Keychain Access**, search
for `com.honestlymylove.isftp`, and delete the matching entries. Deleting the app
does not automatically remove Keychain items that macOS retains. Server logs for
this website are kept only as long as the hosting provider's standard retention
period and are then discarded.

## Security

Credentials and host keys are stored in the macOS Keychain. SFTP, FTPS, and
WebDAVS connections are encrypted in transit. Postern verifies SSH host keys and
refuses an unknown or changed key until you approve it in the app.

No method of storage or transmission is completely secure, but Postern is
designed to keep your information on your Mac and on the servers you choose.

## Children

Postern is a general-purpose utility and is not directed at children. We do not
knowingly collect information from anyone, including children under 13.

## Your rights

Other than the standard server logs described above, we do not collect personal
information, so there is generally nothing for us to access, correct, export, or
delete on your behalf. If you believe we hold
information about you, contact us and we will respond. Nothing in this policy
limits rights you have under applicable law.

## Changes

If this policy changes, we will update the effective date above and, for material
changes, note them in the app or on this page.

## Contact

Email **support@honestlymylove.com**. We aim to reply within two business days.

Support: <https://postern.honestlymylove.com/site/support/>
