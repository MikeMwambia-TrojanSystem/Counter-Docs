## order5.jsx

**Route:** `/order5`
**Purpose:** Final confirmation screen — payment verified, order marked complete, displays transaction summary.

**Props**
<!-- fill in -->

**State**
<!-- fill in -->

**Data displayed**
| Field | Example shown |
|---|---|
| M-Pesa pay code | 4QA3456G — Payment received |
| POKT receiving address | pokt132v39vh24y7z8hyhs43fq5pezuasfmt2smq3gl |
| Ethereum amount | 0.5 |
| Amount paid (Kshs) | 100,000 |
| Order status | Completed |
| Settlement note | ~15 secs for ETH to be sent and reflect on the receiving address, after which order status updates |

**API calls**
<!-- fill in: does this page poll the chain/POKT gateway to confirm the ETH transfer landed, or does it just display a static "completed" state once order4's verify call succeeds? -->

**Actions**
<!-- fill in: any actions on this screen (e.g. "return to dashboard", "view on explorer")? not visible in screenshot -->

**Validation**
N/A — display-only confirmation screen.

**Known issues / open questions**
- Amount paid (100,000 Kshs) doesn't match the 18,500 Kshs payment instruction shown in order3 for the same 0.5 ETH — confirm whether this is a data/test inconsistency or whether order3 and order5 represent different transactions reused for screenshots.
