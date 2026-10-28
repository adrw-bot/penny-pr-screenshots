# Slack tab follow-ups (getpenny/penny, follow-up to #877 / #878)

Local dev only, with a mocked Slack API (a local stand-in answering auth.test, conversations.list, conversations.info and users.list). Penny CPA fixture workspace. Nothing reached Slack.

- slack-id-entry-resolved.png: a channel ID pasted, checked with conversations.info, named.
- slack-not-member-invite-hint.png: a channel link where PennyBot isn't a member: saved, with the /invite @PennyBot hint.
- slack-channel-not-found.png: channel_not_found inline error, typed value kept, Retry.
- slack-refresh-channels.png: PennyBot added to a channel, Refresh channels lists it.
- slack-autosave-saved.png: picking a channel saves at once (Saved), no Save button.
