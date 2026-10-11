# Privacy policy: YouTube DJ Set Tracklist Overlay

**Last updated:** 2026-10-11

This policy describes how the YouTube DJ Set Tracklist Overlay Chrome
extension handles information.

## What the extension does

The extension adds a tracklist overlay to YouTube watch pages. When you use
the overlay, it uses the current video's public YouTube URL to search
1001tracklists.com for a matching DJ set tracklist. The video's title and
channel name are read locally to improve matching.

## Data processed

The extension may process:

- the current YouTube video URL and video ID;
- the current video's displayed title and channel name, for local matching;
- tracklist page content returned by 1001tracklists.com;
- your selected panel dimensions;
- the resolved tracklist associated with a video ID.

The extension does not require an account, collect names or email addresses,
or intentionally collect browsing history beyond the current video on which
you activate the feature. The title and channel name are not sent to the
extension publisher or included in the search request.

## Where data goes

When you activate the feature, the extension sends the current video's public
YouTube URL as a search query to 1001tracklists.com using the browser. It may
open a temporary 1001tracklists.com tab when that site requires browser-based
verification. That tab may use the site's own cookies and security checks
under the site's privacy policy and terms.

The extension does not operate a separate analytics, advertising, or
publisher-operated application backend. It does not sell personal information
or send extension data to an operator-controlled server.

## Local storage and retention

Resolved tracklists and the panel size are stored locally in Chrome storage
on your device. Tracklist cache entries expire after 30 days. Invalid or
expired entries are removed automatically. The panel size remains in local
extension storage until it is changed or the extension is uninstalled.

## Permissions

- `storage` stores the local cache and panel preferences.
- `offscreen` parses fetched HTML in a DOM-capable extension context.
- `tabs` validates messages from the current YouTube tab and observes, reads,
  and closes temporary 1001tracklists.com verification tabs.
- `scripting` reads rendered 1001tracklists.com HTML and performs same-origin
  requests inside a temporary site tab when browser verification is required.
- Host access is limited to YouTube content pages and
  `https://www.1001tracklists.com/*` for the documented feature.

## Third-party services

The extension depends on YouTube and 1001tracklists.com. Their services,
policies, availability, cookies, and content are controlled by those
providers. The extension is not affiliated with or endorsed by either
provider.

## Chrome Web Store User Data Policy

Information handled by the extension is used only to provide, maintain, and
secure its tracklist overlay feature. It is transferred to 1001tracklists.com
only when necessary to perform a user-requested tracklist search or retrieve a
selected tracklist. The extension does not sell user data, use it for
personalized advertising, or allow humans to review it for unrelated
purposes. The extension's use of information complies with the Chrome Web
Store User Data Policy, including the Limited Use requirements.

## Security and contact

All data transmitted by the extension to its documented third-party service
uses HTTPS. Report extension security or privacy concerns through the
publisher's official support contact: **matradevs@gmail.com**.

## Changes

If the extension's data practices change, update this policy and the Chrome
Web Store privacy disclosures before shipping the change.
