# Rate Limiting

Rate limiting controls how fast users can act.
It is an effective integrity tool.

## Common actions to limit

- Account creation
- Profile edits
- Swipes or likes
- First messages
- Link sharing
- Image uploads
- Reports filed

Limits should vary by context.

## Why rate limiting works

- It slows scripted abuse.
- It reduces spam volume.
- It increases effort for bad actors.
- It protects systems during attacks.

Most legitimate users never hit limits.

## Progressive friction

Limits should increase gradually.
Hard blocks come later.

Examples:
- Fewer likes per hour for new accounts
- Message delays after rapid sending
- Temporary cooldowns instead of bans

This preserves trust.

## Failure modes

- Limits that are too strict hurt new users.
- Static limits are easy to game.
- Silent limits confuse users.
- Global limits punish the wrong people.

## Open questions

- When should limits decay?
- How should limits differ by account age?
- When should users be told they hit a limit?
