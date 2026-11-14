---
title: Tab Compass privacy policy
permalink: /privacy/
---

# Tab Compass privacy policy

Effective 14 November 2026.

Tab Compass is a browser extension that organizes your open tabs, in Firefox, Chrome and Microsoft Edge. It has no servers, no accounts, no analytics and no ads. Its developer never receives any of your data.

## What Tab Compass reads

To sort your tabs, it reads, inside your browser:

- each open tab's address, title and site, and when you last used it;
- if you allow page reading, a short digest of each page: its title, description, main headings and the first 1,600 or so characters of its text. On pages with a password or payment-card field, only the title, description and headings;
- when you ask for a summary of a page, that page's main text, at that moment. Never on a page with a password or payment-card field.

Tabs in private windows are never read. Tabs that another add-on has hidden are left alone.

## What it stores, and where

Everything below stays in your browser's extension storage, on your computer, and isn't synced anywhere:

- **Page digests**, so tabs that are unloaded later still sort well. Each is deleted after 30 days. You can turn this off in Settings, which deletes what's been remembered; so does withdrawing page reading.
- **Your settings**, including any AI provider key you enter.
- **Backups of your open tabs**: every 10 minutes, if they changed, each tab's address and title, with its window, tab group, pinned state and, in Firefox, its container. Private windows are never included. It keeps the newest 10, the last one of each of the past 14 days, up to 10 you made yourself, any you choose to keep, and up to 5 full ones from before your browser came back with far fewer tabs. You can change how often, or turn backups off, in Backups & export.
- **Saved lists** ("Save & close", from the dashboard, the toolbar button or the right-click menu, and tidying up if you turn it on): the addresses and titles of the tabs and, in Firefox, the container each was in.
- **Snoozed tabs**: the same, plus the time they're due back. Once they're back, a short note of what came back (its name and how many tabs) stays until you open the toolbar popup or the dashboard.
- **Focus** (Firefox): while focus hides tabs, the addresses of the hidden tabs, so they can be shown again even after a restart. Deleted when focus ends.
- **Sites to keep open**, and **sites never checked for duplicates**: the site names you list in Settings.
- **Duplicate tabs and saved pages**, only while your browser is running and gone when it quits: the numbers the browser gives the tabs you've just opened and the tabs Tab Compass is pointing out; the address each tab Tab Compass opened for you started with (so it isn't pointed out as a page you saved); and numbers worked out from the addresses in your saved and snoozed lists, to spot those pages quickly.
- **Summaries** you ask for: the page's address and title, the summary, and which model made it, for the newest 300. When you save a page for later, its summary stays with its link.
- **Days you used your browser**: just the dates (the last 120), so tidying up counts only those days.
- **The last AI result**, if you use AI, until you choose "Forget AI results" or organize again.

Only if you ask for them:

- **Bookmarks**: "Bookmark", "Bookmark all topics", and the setting that bookmarks what you save and close, add normal bookmarks in Other Bookmarks › Tab Compass. If your browser syncs your bookmarks, it syncs these like any other.
- **Files**: export and "Save as a file" save a file to your Downloads folder when you click them. If you turn on the daily copy, a backup file is saved in Downloads › Tab Compass backups once a day (one per weekday, overwritten the next week). Backup files include your saved and snoozed lists, and a signature made with a random key that stays in this browser profile's storage, so Tab Compass can tell its own, unchanged files from anyone else's: only those bring back containers and snoozes.

Removing the extension deletes everything in its storage. Bookmarks and files it made for you stay until you delete them.

## What leaves your computer

Nothing, unless you use the optional AI features.

When you press **Organize with AI** and confirm, Tab Compass sends this to the provider you chose in Settings:

- for each loose tab: a number, how long ago you used it, its site name, and its title (for a search page, what you searched for);
- if "Also send a short snippet of each page" is on, about 160 characters from the page's description or opening text.

It never sends pinned tabs, tabs in your own tab groups, mail and chat tabs (such as Gmail, Outlook, Slack, WhatsApp, ChatGPT and Claude), private-window tabs, full page text, or full page addresses.

Before anything is sent, Tab Compass shows how many tabs and roughly how many tokens. The first time, your browser also asks you to let Tab Compass reach that provider (Firefox also asks for your consent to send the data); you can take this back in your browser's settings for Tab Compass. The request goes directly from your browser to the provider, using your own API key; Tab Compass's developer is not involved and doesn't see it.

When you ask for a **summary of a page** (from the right-click menu, the toolbar popup, the dashboard or a keyboard shortcut), Tab Compass sends that page's own title and its main text, as shown, and nothing else: not its address, and nothing about your other tabs. It never sends a page from a private window, a mail or chat page, a search results page, a checkout or payment page, or a page with a password or payment-card field, and nothing if the tab has gone to another page since you asked. The first time with each online provider, Tab Compass shows what it would send and roughly what it costs, and your browser asks for your permission; after that, summaries with that provider go straight through, unless you ticked "Ask me every time".

If you choose a model running on your own computer (Ollama, LM Studio, or another server at a localhost address), the request goes only to that program, which may pass it on: Tab Compass treats Ollama's cloud models, and any server at another address, as online, and asks first.

What a provider does with a request is covered by its own privacy policy: [Anthropic](https://www.anthropic.com/legal/privacy), [OpenAI](https://openai.com/policies/privacy-policy), [Google](https://policies.google.com/privacy), [OpenRouter](https://openrouter.ai/privacy), or whoever runs the server you entered.

Tab Compass uses what it reads only for the features described here, never sells or shares it, and never uses it for advertising or to judge creditworthiness. Its use of this information complies with the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Permissions, and why

- **Tabs**: to list your tabs, switch to them, and close and reopen them.
- **Access your data for all websites** (optional, asked on the welcome page or the dashboard, not at install): to read the page digests described above, and to reach the AI provider you chose. You can refuse or withdraw it; Tab Compass then works from titles only, and deletes the page digests it kept.
- **Scripting**: to run the small page reader in your tabs, and, when you ask for a summary, the one that reads that page's main text.
- **Storage**: to keep your settings, saved lists, backups and page digests. In Chrome and Edge, also **unlimited storage**, so a large backup isn't cut off at the browser's usual limit.
- **Tab groups**: to show your own tab groups, and to create, change, merge, move and ungroup them when you ask.
- **Alarms**: to make the backups, tidy up and bring snoozed tabs back on time.
- **Menus**: for Tab Compass's items when you right-click a tab (in Chrome and Edge, a page) or the toolbar button.
- **Side panel** (Chrome and Edge): to show Tab Compass and summaries next to the page.
- **Bookmarks** (optional, asked for the first time you bookmark something): to add the bookmarks described above. Tab Compass doesn't read your other bookmarks.
- **Downloads** (optional, asked for when you turn on the daily copy): to save the backup file in your Downloads folder.
- **Hide and show tabs** (Firefox; optional, asked for the first time you use Focus): to hide the other tabs while you focus, and show them again.
- **Cookies** (Firefox): only so a saved or backed-up tab can reopen in the same container it came from. Tab Compass doesn't read or change any cookies.
- **Optional data collection** (Firefox; browsing activity, website content, search terms): Firefox asks for these only when you use AI with an online provider: to organize your tabs, or to summarize a page (website content).

## Changes

If this policy changes, the new version ships with the extension's update, with a new date at the top, and is published at https://yiorgos-p.github.io/tab-compass/privacy/.

## Contact

Open an issue at https://github.com/yiorgos-p/tab-compass/issues, or use the support details on Tab Compass's page in your browser's add-on store.
