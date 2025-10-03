# cybersecurity7
Browser Extension Security Review
📌 Objective
Learn to spot and remove potentially harmful browser extensions, ensuring the browser remains secure and lightweight.
🔧 Tools
Google Chrome browser (Extensions Manager: chrome://extensions/).
📝 Steps Performed
1. Open Extensions Manager
Opened Chrome.
Navigated to chrome://extensions/.
2. Reviewed Installed Extensions
Observed installed extensions:
Adobe Acrobat (PDF edit, convert, sign tools)
Google Docs Offline
McAfee WebAdvisor (security add-on)
[Other extensions may be listed further down]
3. Checked Permissions & Usefulness
Adobe Acrobat: Trusted vendor, useful for PDF handling.
Google Docs Offline: Official Google extension, needed for offline editing.
McAfee WebAdvisor: Provides browsing protection, but may slow down performance; optional depending on user preference.
4. Identified Suspicious/Unused Extensions
No unknown or untrusted extensions found.
All visible extensions are from legitimate vendors (Adobe, Google, McAfee).
Recommendation: Remove extensions that are unused to reduce attack surface.
5. Removed or Kept Extensions
| Extension Name      | Action Taken | Reason                                |
| ------------------- | ------------ | ------------------------------------- |
| Adobe Acrobat       | Kept         | Trusted, useful for PDFs              |
| Google Docs Offline | Kept         | Trusted, required for offline use     |
| McAfee WebAdvisor   | Optional     | Security add-on, but may impact speed |
6. Restarted Browser
Restarted Chrome after reviewing extensions.
No performance issues observed.
🔎 Research on Malicious Extensions
Malicious browser extensions can:
Steal credentials or browsing history.
Redirect searches to malicious websites.
Inject ads and trackers.
Download additional malware in the background.
