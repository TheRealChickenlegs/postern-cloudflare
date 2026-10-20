# Postern Support

Postern connects to SFTP, FTP, FTPS, WebDAV, and WebDAVS servers and shows them
in Finder, so you can browse, copy, rename, and delete files like any folder.

## At a glance

- Requires macOS 14 or later.
- Connections appear under **Locations** in Finder's sidebar.
- The free version allows one saved connection per protocol. Postern Full
  removes that limit with a one-time purchase.

## Getting started

1. Open Postern and choose **Add Connection**.
2. Enter a name, choose the protocol, and fill in the server, port, username, and
   either a password or an SSH key. Optionally set a starting directory.
3. Save. Postern connects and the server appears in Finder.
4. In Finder, open the sidebar and select the entry under **Locations**. With one
   connection it is labelled **Postern**; with more than one it is
   **Postern - <name>**.

## Enable the Finder extension once

macOS requires you to turn on the File Provider extension before Postern can
appear in Finder:

1. Open **System Settings → General → Login Items & Extensions**.
2. Under Extensions, open **Postern Extension** (listed under File Provider).
3. Turn on **File Provider** for Postern.

If the entry does not appear, quit and reopen Postern, then check again. This is
a one-time step.

## Using connections

- The menu bar icon lists your connections. Use it to connect, disconnect, or
  show a connection in Finder.
- Keep Postern running while you use a server on your network: the app relays
  that connection to the Finder extension. Quitting the app disconnects active
  servers.
- Drag and drop, copy and paste, rename, create folders, and delete work as they
  do for local files.
- Deleting a connection in Postern also removes its saved credentials from your
  Keychain.

## Free version and Postern Full

The free version allows one saved connection for each protocol. To add more,
choose **Unlock Postern** and purchase Postern Full once. It is a one-time,
non-consumable purchase tied to your Apple Account.

If you reinstalled the app or use another Mac, choose **Restore Purchases** in
the unlock window.

Purchases are handled by Apple. For refunds, use
[Report a Problem](https://reportaproblem.apple.com).

## Troubleshooting

| Symptom | What to try |
| --- | --- |
| Postern does not appear in Finder | Enable the extension (above), then quit and reopen Postern. |
| The entry says only "Postern", not my connection name | With a single connection macOS labels the entry with the app name. The connection name appears once you add a second one. |
| Cannot connect to a server on my network | Make sure Postern is running, since the app relays the connection. Check the address, port, and that the server is reachable from your Mac. |
| Authentication failed | Re-enter the password, or check that the SSH key is an OpenSSH key (for example `id_ed25519`) and that the username is correct. |
| Host key changed or not trusted | Postern refuses an unknown key. Verify the fingerprint with your server administrator, then approve it in Postern. Use **Forget Recorded Key** if the server legitimately changed its key. |
| Connection drops when I quit Postern | Expected for network servers: the relay runs in the app. Keep Postern open while connected. |
| FTP connection is rejected | Some servers require FTPS (explicit TLS) or SFTP. Try the matching protocol and port. |

## Security tips

- Prefer SFTP, FTPS, or WebDAVS. Plain FTP sends credentials and files
  unencrypted.
- Approve SSH host keys only after checking the fingerprint with someone you
  trust.
- Do not send passwords or private keys in a support request.

## Contact

Email **support@honestlymylove.com**. Please include:

- the Postern version (select Postern in Applications and press Command-I);
- your macOS version;
- the protocol and server address (never credentials);
- the exact error message.

We aim to reply within two business days.

Privacy policy: <https://postern.honestlymylove.com/site/privacy-policy/>
