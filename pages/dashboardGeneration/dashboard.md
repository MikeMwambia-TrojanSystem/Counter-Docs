## order3.jsx

**Route:** `/dashboard`
**Purpose:** Displays locked order details and payment instructions; order enters pending state.

**Props**
<!-- fill in -->

**State**
<!-- fill in: order ID, payment status -->

**Data displayed**
| Field | Example shown |
|---|---|
| Ethereum price for this transaction | Ksh 245,000 |
| Payment amount | Ksh 18,500 |
| Paybill number | 4107329 |
| Receiving ETH amount | 0.5 Eth |
| Receiving address | pokt132v39vh24y7z8hyhs43fq5pezuasfmt2smq3gl |
| Account number (for paybill payment) | ORDER2354 |
| Order status | PENDING PAYMENT |

**API calls**
<!-- fill in: is order locked/created via an API call on this page load, or was it created in order2? does this page poll for payment confirmation? -->

**Actions**
| Control | Behavior |
|---|---|
| Next (implied — "click next to enter mpesa payment code") | <!-- fill in: navigates to order4 --> |

**Validation**
N/A — display-only screen, no inputs.

**Known issues / open questions**
<!-- fill in: confirm how long an order stays "locked" before expiring if payment isn't made -->

---
