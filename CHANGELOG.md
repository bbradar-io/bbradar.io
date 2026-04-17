# Changelog

All notable changes to bbradar.io are documented here. Dates use DD/MM/YYYY.

**17/04/2026**

- 📝 Profile: Refreshed README feature coverage and regenerated the public screenshots from the current live UI
- 🔎 Discovery: Documented the current Pro API, report-count metadata, platform intelligence, community voting, target monitoring, and expanded platform coverage
- 🖼️ Screenshots: Updated dark/light program views, latest targets/Pro alerts, platform intelligence, and the root preview image

**16/04/2026**

- 🎯 Targets: Refactored target handling, target-change filters, program target summaries, and target detail rendering
- 🧩 UX: Added target identifier copy buttons on program details and target-change cards
- 🏷️ Tags: Expanded AI/ML, language, package, smart-contract, domain, wildcard, and asset identifier normalization
- 📈 Reports: Added report-count metadata, Pro-only report counts, sorting support, and upsell/unavailable states
- 🔁 Fetching: Added configurable Bugcrowd, Intigriti, HackenProof, and Immunefi fetch limits, delays, retries, and timeouts
- 🐛 Fix: Improved duplicate host extraction, scope-type consistency between program lists and target views, API key reissues, and cron/database error handling

**09/03/2026**

- 🔑 Pro API: Added API key management, Pro API docs, endpoint aliases, per-key rate limits, lockout handling, and program/target API access
- 🔐 Auth: Hardened OAuth redirects, forwarded protocol handling, trusted proxy behavior, CSRF exemptions, and real client IP handling
- 📣 Pro: Added dismissible Pro API homepage banner and improved account API key management
- 🚦 Infra: Added dedicated API proxy configuration and production Nginx handling for Pro API traffic

**19/01/2026**

- 🌐 Platforms: Added Cantina and GoBugFree coverage to public docs and platform stats
- 📊 Analytics: Added Platform Intelligence with platform voting, popularity rankings, 90-day trend windows, VDP share, reward profiles, and daily snapshots
- 🗳️ Community: Added automatic vote refresh and improved platform/program vote labels
- 🔎 SEO: Updated Pro and target-search metadata for live alerts and enhanced target search

**31/12/2025**

- 💳 Pro: Added Stripe payments, subscriptions, billing portal flows, Pro overrides, account billing UI, payment policy, and terms updates
- 📣 Notifications: Added Discord program notifications, target-change notifications, billing notifications, and notification retention/deduplication controls
- 🧰 Operations: Added database backups, billing audit tables, Pro override storage, Docker log rotation, and MySQL configuration tuning
- 🌙 UI: Improved dark mode support across program cards, target cards, headers, footers, search, and content pages

**26/11/2025**

- 🔐 Accounts: Added Google sign-in and authenticated user sessions
- 🗳️ Voting: Added program voting, vote labels, vote sorting, and rendered voting results as ratings
- 📱 UI: Improved mobile header behavior, program cards, deploy scripts, and HTTPS/DNS deployment configuration

**10/10/2025**

- 🎯 Targets: Added Latest Targets page, target-change history, target filters, target search, target structured data, and program detail target views
- 🌐 Platforms: Expanded target extraction across HackerOne, Bugcrowd, HackenProof, Immunefi, YesWeHack, BugBase, Remedy, Code4rena, and IssueHunt
- 🔁 Fetching: Improved Bugcrowd fetch speed, HackerOne target handling, scope detection, exchange-rate configuration, and target retention

**18/09/2025**

- 🧹 Discovery: Hid VDP programs by default and added a toggle to show VDP programs
- 🔎 SEO: Fixed sitemap and program-detail structured data handling

**31/08/2025**

- 🐛 Fix: wildcard tags now properly work across all platforms
- 🐛 Fix: Resolved small UI sorting issue

**28/08/2025**

- 🌐 Platforms: Added IssueHunt and BugRap platforms
- ❓ FAQ: Added FAQs

**28/07/2025**

- 🎨 UI: Full redesign
- ✨ Feature: Added bounty amount data point
- 🔧 Improvements: Many other features and fixes

**03/11/2024**

- ✨ Feature: Added Web2/Web3 category tabs

**28/10/2024**

- 🔁 Fetching: Updated HackenProof program fetching
- 🧰 Feature: Added Bug Bounty Tools section
- ⚙️ Backend: Optimized several backend workflows

**30/07/2024**

- 🖼️ Branding: Updated HackenProof logo
- ⚡ Performance: Optimized speed and refresh time
- 🐛 Fix: Resolved temporary issue with missing programs

**05/07/2024**

- 🌐 Platforms: Added Remedy platform
- ✨ Feature: Added new platforms section

**26/06/2024**

- 🧹 Data quality: Filtered out programs with future dates

**18/06/2024**

- 🌐 Platforms: Added BugBase platform
- 🐛 Fix: Corrected datetime handling across platforms

**04/03/2024**

- ⏱️ UX: Switched to full Datetime (instead of Date)
- ✨ Feature: Added Program Type to the list; searchable/sortable via the universal search bar
- ⚙️ Backend: Increased refresh cadence to ~10 minutes
