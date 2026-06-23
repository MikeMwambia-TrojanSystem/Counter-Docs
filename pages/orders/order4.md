## order4.jsx

**Route:** `/order4`
**Purpose:** Buyer submits their M-Pesa payment code to verify payment was made.

**Props**
<!-- fill in -->

**State**
<!-- fill in: payment code input value -->

**Form fields**
| Field | Example | Type `<!-- fill in -->` | Required? `<!-- fill in -->` |
|---|---|---|---|
| M-Pesa payment code | (free input) | string | yes |

**API calls**
<!-- fill in: endpoint that verifies the M-Pesa code against the paybill transaction — likely calls Safaricom Daraja API or an internal reconciliation service, confirm -->

**Actions**
| Control | Behavior |
|---|---|
| Verify | <!-- fill in: navigates to order5 on success — what happens on failure/invalid code? --> |

**Validation**
<!-- fill in: confirm Verify is disabled until a code is entered — appears disabled in screenshot -->

**Known issues / open questions**
- Verify button appears disabled in the screenshot — confirm exact enabling condition.
- <!-- fill in: confirm error handling/messaging if the entered code doesn't match a real payment -->
