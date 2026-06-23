## order.jsx

**Route:** `/order`
**Purpose:** Order summary screen shown before a buyer commits to an order — displays the dashboard's current rate and purchase limits.

**Props**
<!-- fill in: dashboard ID likely passed via route param or context — confirm -->

**State**
<!-- fill in -->

**Data displayed**
| Field | Example shown | Source `<!-- fill in: fetched from dashboard config / live oracle -->` |
|---|---|---|
| Dollar rate | Kshs per $1 (value blank in screenshot — confirm rendering bug or just empty test data) | |
| Minimum purchase | KSHs | |
| Maximum purchase | KSHs | |
| Asset price | KSHs for 1.0000 Ethereum at $X | |

**API calls**
<!-- fill in: endpoint fetching dashboard rate/limits, and whether asset price is live-polled here or fetched once on load -->

**Actions**
| Control | Behavior |
|---|---|
| Lock order | <!-- fill in: navigates to order1? does it reserve the rate for a time window? --> |
| Return to dashboard | <!-- fill in: navigates back to which dashboard route --> |

**Validation**
N/A — display-only screen, no inputs.

**Known issues / open questions**
- Screenshot shows blank values for dollar rate, min/max purchase, and dollar price — confirm whether this is a data-loading bug or just an unconfigured test dashboard.
