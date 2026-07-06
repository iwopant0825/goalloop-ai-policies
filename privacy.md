# GoalLoop AI Privacy Policy

Last updated: 2026-07-07

GoalLoop AI is a Chrome extension that adds a Codex Goal-style completion layer on top of ChatGPT, Claude, and Gemini. Its single purpose is to help users define a goal, verify whether the latest AI response satisfies the goal criteria, and prepare the next user-approved prompt when work is incomplete.

## Single Purpose

GoalLoop AI is a productivity extension for supported AI chat websites. It provides one narrow function: goal completion verification and user-approved continuation prompts for the active chat task.

## Data Stored Locally

GoalLoop stores the minimum local data needed to provide the feature:

- Goal contracts, completion criteria, and output preferences.
- Compact verification evidence summaries.
- Saved user templates.
- Extension settings.
- Optional provider configuration and API key, stored in Chrome extension local storage and used only by the extension service worker.

GoalLoop does not intentionally persist full raw chat transcripts by default.

## Data Sent To Third Parties

GoalLoop can run without an external AI provider. When the optional NVIDIA provider is enabled, GoalLoop sends only the current goal, missing criteria, and compact evidence context needed to draft a better follow-up prompt. Provider assist is used to help compose user-reviewed prompts; deterministic local verification remains the primary completion decision path.

GoalLoop does not sell user data, use user data for personalized advertising, transfer user data to data brokers, or use user data to determine creditworthiness or lending eligibility.

## User Control

GoalLoop does not submit prompts without a direct user action. The user can edit the goal, criteria, generated prompt, provider settings, and saved templates before continuing.

Users can disable provider assist by removing the NVIDIA API key from the extension options page. Users can also remove local GoalLoop data from the options page or through Chrome's extension storage controls.

## Chrome Web Store Limited Use Statement

GoalLoop AI's use of information received from Chrome extension APIs adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements. Data is used only to provide or improve the extension's single purpose: goal completion verification and user-approved prompt continuation inside supported AI chat sites.

GoalLoop does not collect background browsing history. It runs only on the supported AI chat hosts declared in the extension manifest and uses visible page content only for the user-facing GoalLoop workflow.

## Security

Provider calls use HTTPS. API keys are not embedded in packaged extension code and must be supplied by the user or a future account backend. Production paid deployments should use account-level quota controls and should not distribute a shared provider key inside the extension package.

## Support

For public distribution, the Chrome Web Store listing should expose the developer support contact and link to this privacy policy from the listing or a page one click away from the listing.
