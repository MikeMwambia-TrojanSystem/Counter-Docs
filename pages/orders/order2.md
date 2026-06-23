## order2.jsx

**Route:** `/order2`
**Purpose:** Buyer enters the destination crypto address for the Ethereum.

**Props**
<!-- fill in -->

**State**
<!-- fill in: address input value -->

**Form fields**
| Field | Example | Type `<!-- fill in -->` | Required? `<!-- fill in -->` |
|---|---|---|---|
| Receiving crypto address | (free input) | string, address format | yes |

**API calls**
<!-- fill in: is the address format validated client-side (checksum/regex) or server-side on submit? -->

**Actions**
| Control | Behavior |
|---|---|
| Validate order | <!-- fill in: navigates to order3, what validation runs before proceeding --> |

**Validation**
<!-- fill in: confirm address format check exists — button appears disabled in screenshot, presumably until a valid-looking address is entered -->

**Known issues / open questions**
- Validate order button appears disabled in the screenshot — confirm exact enabling condition (non-empty field vs. actual address format check).
