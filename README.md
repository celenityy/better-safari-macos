# better-safari-macos

My recommendations for the ultimate configuration of the Safari Browser on macOS :)

# General

**Safari opens with:** -> `A new window`

**Remove history items:** -> `After one day`

**File download location:** -> `Ask for each download`

**Remove download list items:** -> `When Safari quits`

**Open "safe" files after downloading** -> ❌

# Tabs

**Automatically close tabs:** -> `After one day`

# AutoFill

You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead.

AutoFill web forms:

**Using information from my contacts** -> ❌

**User names and passwords** -> ❌

**Credit cards** -> ❌

**Other forms** -> ❌

# Passwords

Security Recommendations -> **Detect Leaked Passwords** -> ✅ *(This is done locally on device through a list of passwords, Apple doesn't get sent your passwords)*

Password Options -> **AutoFill Passwords and Passkeys** -> ❌

Password Options -> Verification Codes -> **Delete After Use** -> ✅

# Search

**Search engine:** -> `DuckDuckGo`

Search engine: -> **Also use in Private Browsing** -> ✅

**Private Browsing search engine:** -> `DuckDuckGo`

Private Browsing search engine: -> **Include search engine suggestions** -> ❌

Smart Search field: -> **Include Safari Suggestions** -> ❌

Smart Search field: -> **Preload Top Hit in the background** -> ❌

# Security

Fraudulent sites: -> **Warn when visiting a fraudulent site** -> ✅ *(Should be default)*

Web content: -> **Enable JavaScript** -> ✅ *(Should be default, disabling this WILL cause breakage and doesn't appear to be toggable per-site, not worth the trouble IMO)*

# Privacy

Website tracking: -> **Prevent cross-site tracking** -> ✅

Hide IP address: -> **Hide IP address from trackers** -> ✅

# Websites

Content Blockers -> **When visiting other websites:** -> `On`

Auto-Play -> **When visiting other websites:** -> `Never Auto-Play`

Camera -> **When visiting other websites:** -> `Deny` *(Obviously don't set if you use sites that need camera access, but you can still set exceptions for sites if needed)*

Microphone -> **When visiting other websites:** -> `Deny` *(Obviously don't set if you use sites that need microphone access, but you can still set exceptions for sites if needed)*

Screen Sharing -> **When visiting other websites:** -> `Deny` *(Obviously don't set if you constantly need to screen share on web, but you can still set exceptions for sites if needed)*

Location -> **When visiting other websites:** -> `Deny`

Downloads -> **When visiting other websites:** -> `Ask`

Notifications -> **Allow websites to ask for permission to send notifications** -> ❌

Pop-up Windows -> **When visiting other websites:** -> `Block and Notify` *(You could also set to `Block` if you're annoyed by the notifications)*

# Advanced

Smart Search field: -> **Show full website address** -> ✅

Privacy: -> **Use advanced tracking and fingerprinting protection** -> ✅

Privacy: -> Use advanced tracking and fingerprinting protection -> `in all browsing`

Privacy: -> **Allow websites to check for Apple Pay and Apple Card** -> ❌

Privacy: -> **Allow privacy-preserving measurement of ad effectiveness** -> ❌

# Start Page 

*Settings icon on bottom right*:

**Frequently Visited** -> ❌

**Shared With You** -> ❌

**Recently Closed Tabs** -> ❌

# Additional recommendations

* Follow my macOS settings [here](https://codeberg.org/Magnesium1062/macos-settings).

* Use a content blocking extension like [AdGuard](https://apps.apple.com/app/adguard-for-safari/id1440147259). *See my recommended settings [here](https://codeberg.org/Magnesium1062/adguard-safari-settings-macos)*.

* Use a private, secure, & reputable DNS provider of your choice. I would recommend setting up your own [NextDNS](https://nextdns.io) configuration if you are able to (See my recommendations for NextDNS [here](https://codeberg.org/Magnesium1062/nextdns-settings)), otherwise I would recommend [Quad9](https://quad9.net/): `https://dns.quad9.net/dns-query`.

* Enable [Lockdown Mode](https://support.apple.com/105120).

* Use a (reputable) VPN. I would recommend either [Mullvad](https://mullvad.net/) or [ProtonVPN](https://protonvpn.com/).