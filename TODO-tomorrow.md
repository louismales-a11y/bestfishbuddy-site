# Tomorrow (July 6, 2026) — GoDaddy DNS Setup

## 1. Point www.bestfishbuddy.com to GitHub Pages

At GoDaddy, add these DNS records for `www.bestfishbuddy.com`:

| Type | Name | Value |
|------|------|-------|
| A | www | `185.199.108.153` |
| A | www | `185.199.109.153` |
| A | www | `185.199.110.153` |
| A | www | `185.199.111.153` |
| AAAA | www | `2606:50c0:8000::153` |
| AAAA | www | `2606:50c0:8001::153` |
| AAAA | www | `2606:50c0:8002::153` |
| AAAA | www | `2606:50c0:8003::153` |

(Typically under "Advanced Settings" → "Manage DNS" in GoDaddy)

## 2. Log into tinyurl.com and update the three aliases

Change each alias's destination URL:

| Alias | New destination |
|-------|----------------|
| `bfbfree1914` | `https://www.bestfishbuddy.com/free` |
| `bfbpro1914` | `https://www.bestfishbuddy.com/pro` |
| `bfbdev1914` | `https://www.bestfishbuddy.com/dev` |

## 3. Tell the assistant

Once both steps are done, the assistant can take over all future URL updates — no more manual TinyURL edits needed.
