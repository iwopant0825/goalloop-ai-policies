# GoalLoop AI Terms

Last updated: 2026-07-07

Public URL: `https://github.com/iwopant0825/goalloop-ai-policies/blob/main/terms.md`

## Service Scope

GoalLoop AI provides goal completion verification, editable criteria, Done Proof summaries, local history, templates, and optional provider-assisted continuation prompts on supported AI chat sites.

## User Control

- GoalLoop does not send continuation prompts without a direct user action.
- GoalLoop does not guarantee that an AI assistant response is factually correct.
- Users remain responsible for reviewing, editing, and approving all AI-generated output.
- Users should not enter secrets, regulated personal data, or confidential third-party data unless their own policies allow it.

## Provider Assist

Provider assist is optional. A user-owned provider key remains local to the browser. A managed paid provider feature must use a backend proxy with quota, abuse controls, and redaction.

## Paid Plans

Paid plans may unlock managed provider assist, longer history limits, team templates, and quota-managed workflow support. The extension package must not contain a shared NVIDIA key, payment secret, backend secret, or customer token.

## Availability

GoalLoop depends on supported chat sites and browser extension APIs that can change. If a site changes its UI, GoalLoop may need an update before all workflows work again.

## Support

Support requests go to `https://github.com/iwopant0825/goalloop-ai-policies/issues`. Diagnostics should avoid raw private transcripts unless the user explicitly chooses to share redacted details.
