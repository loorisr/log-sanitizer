# Log Sanitizer & Anonymizer

A privacy-first browser tool that sanitizes sensitive data from log files. Paste raw logs, get clean logs back — everything runs locally, nothing leaves your browser.

Available at **[loorisr.github.io/log-sanitizer](https://loorisr.github.io/log-sanitizer/)**.

## Sanitization Rules

| Rule | Detects |
|------|---------|
| MAC Addresses | `00:1A:2B:3C:4D:5E` |
| IPv4 | `192.168.1.1` |
| IPv6 | `2001:db8::1` |
| Domains | `example.com` |
| Emails | `user@example.com` |
| UUIDs/GUIDs | `550e8400-e29b-41d4-a716-446655440000` |
| Credit Cards | `4111-1111-1111-1111` |
| Phone Numbers | `+1 (555) 123-4567` |
| Passwords & Secrets | `password=supersecret` |
| Bearer Tokens | `Bearer eyJhbGci...` |
| Cloud API Keys | AWS, Stripe keys |
| SSIDs | `ssid=MyNetwork` |
| Usernames | `user=john_doe` |
| File Paths | `/Users/john/file.txt` |

## Usage

1. Paste raw logs into the **Input** panel
2. Toggle sanitization rules as needed
3. Copy cleaned output

## Privacy

All processing is done locally in your browser. No data is ever sent to any server.
