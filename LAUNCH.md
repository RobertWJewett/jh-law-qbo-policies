# Jewett Law QBO-Clio Sync — App Information / Connect / Reconnect

**Application:** Jewett Law QBO-Clio Sync
**Operator:** The Law Office of Robert Jewett
**Contact:** robert@jewettlaw.net

This is a private, internal command-line tool built by and for the Firm. It is not a hosted web application and has no public sign-in page, because it only ever connects the Firm's own QuickBooks Online company and the Firm's own Clio Manage account -- there is no multi-tenant login for other users.

## How connecting / reconnecting works

An authorized member of the Firm runs the tool's authorization script locally, within the Firm's own computing environment. That script opens QuickBooks Online's standard OAuth 2.0 authorization screen directly in the user's browser, where the Firm signs in with its own QuickBooks Online credentials and grants (or re-grants) access. No credentials are ever seen, stored, or handled by anyone other than the Firm itself and QuickBooks Online's own login page.

This same process is used both for the initial connection and for reconnecting after a disconnect (see the Disconnect page for details).

## Related pages

- End User License Agreement: ./EULA.md
- - Privacy Policy: ./PRIVACY_POLICY.md
  - - Disconnect information: ./DISCONNECT.md
   
    - ## Contact
   
    - robert@jewettlaw.net
    - 
