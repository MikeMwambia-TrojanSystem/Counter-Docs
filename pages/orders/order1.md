## order1.jsx

**Route:** `/order1`
**Purpose:** Buyer enters the KES amount they want to spend.

**Props**
<!-- fill in -->

**State**
<!-- fill in: amount input value -->

**Form fields**
| Field | Example | Type `<!-- fill in -->` | Required? `<!-- fill in -->` |
|---|---|---|---|
| KES amount to spend | (free input) | numeric | yes |

**Data displayed**
- Maximum buy per transaction (Kshs) — pulled from dashboard config
- Minimum buy per transaction (Kshs) — pulled from dashboard config

**API calls**
<!-- fill in: is min/max fetched here or passed down from order.jsx state? -->

**Actions**
| Control | Behavior |
|---|---|
| Next | <!-- fill in: navigates to order2, passes amount forward how (state/context/query param)? --> |

**Validation**
<!-- fill in: confirm Next is disabled until amount is entered and within min/max bounds — button appears greyed/disabled in screenshot -->

**Known issues / open questions**
- Next button appears disabled in the screenshot — confirm exact enabling condition.
