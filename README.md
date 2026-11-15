# Klein Funding - Discount Codes & Deal History

As of 2026-11, the verified Klein Funding discount code is PFD — 30% OFF, works any time. Its current deals run their own limited-time campaign codes.

> We are Klein Funding, a leading prop trading firm dedicated to empowering traders worldwide. Our mission is to provide innovative funding solutions and advanced tools, enabling traders to unlock their full potential. With a focus on transparency, professionalism, and growth, we support traders in achieving consistent success. Join Klein Funding and take your trading journey to the next level.
>
> — Klein Funding, in its own description on [its Trustpilot profile](https://www.trustpilot.com/review/kleinfunding.com)

- Code: PFD
- Discount: 30% off (headline discount of the code; individual challenge plans on the firm page may list different percentages)
- Valid: standing code — no start date and no end date. It is not a limited-time campaign.
- Last deal published: 2026-02-14
- Trustpilot: [4.8/5 (484 reviews)](https://www.trustpilot.com/review/kleinfunding.com)
- GitHub repository: [https://github.com/propfirmdiscounts/klein-funding-deals](https://github.com/propfirmdiscounts/klein-funding-deals)
- Activate: [https://propfirmdiscount.com/go/kleinfunding](https://propfirmdiscount.com/go/kleinfunding)
- Firm page: [https://propfirmdiscount.com/prop-firm/klein-funding/](https://propfirmdiscount.com/prop-firm/klein-funding/)
- Full dataset: [https://github.com/propfirmdiscounts/prop-firm-discount-codes](https://github.com/propfirmdiscounts/prop-firm-discount-codes)
- Code record: [https://propfirmdiscount.com/api/prop-firm-codes/](https://propfirmdiscount.com/api/prop-firm-codes/)

## Current Klein Funding deal: Klein Funding Valentine's Promo: 5% Off + Bonus Evaluation Account

- Published: 2026-02-14
- Offer ends: Ended
- Offer: 5% off
- Event: Valentine's Day
- Scope: Standard Accounts, Bogo
- Code: this deal carries its own limited-time campaign code, shown on the deal page below
- Deal page: [https://propfirmdiscount.com/deals/klein-funding/klein-funding-valentines-day-standard-account-promo/](https://propfirmdiscount.com/deals/klein-funding/klein-funding-valentines-day-standard-account-promo/)

## Klein Funding discount code FAQ

**What is the Klein Funding discount code?**

PFD. It is verified by PropFirmDiscount.com and takes 30% off Klein Funding challenges and accounts.

**Does the Klein Funding discount code expire?**

No. It is a standing code — there is no start date and no end date. Promotional deals are separate and are dated individually; the current one is listed above.

**How much is the current Klein Funding deal?**

**Klein Funding Valentine's Promo: 5% Off + Bonus Evaluation Account** — published 2026-02-14. Offer ends: Ended. The offer is 5% off.

---

## Deal history

Total deals tracked: **7**

### 2026 (1 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2026-02-14 | Klein Funding: Klein Funding Valentine's Promo: 5% Off + Bonus Evaluation Account | 5% off | Ended | Valentine's Day | [View Deal](https://propfirmdiscount.com/deals/klein-funding/klein-funding-valentines-day-standard-account-promo/) |

### 2025 (6 deals)

| Deal Date | Title | Discount | Expires | Event | Deal Link |
|---|---|---|---|---|---|
| 2025-12-17 | Klein Funding: Deal: 20% Off All Evaluations + Conditional Free Account | 20% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/klein-funding/klein-funding-20-percent-off-evaluations/) |
| 2025-12-17 | Klein Funding: Offer: 10% Off Instant Pro + Conditional Free Account | 10% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/klein-funding/klein-funding-10-percent-off-instant-pro/) |
| 2025-11-27 | Klein Funding: Black Friday Deal: 20% OFF Instant Pro Accounts | 20% off | Ended | Black Friday | [View Deal](https://propfirmdiscount.com/deals/klein-funding/klein-funding-black-friday-20-off-instant-pro/) |
| 2025-11-27 | Klein Funding: Black Friday Sale: 25% OFF All Evaluations | 25% off | Ended | Black Friday | [View Deal](https://propfirmdiscount.com/deals/klein-funding/klein-funding-black-friday-25-off-evaluations/) |
| 2025-10-11 | Klein Funding: Evaluation Promo: 20% OFF + BOGO Special | 20% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/klein-funding/klein-funding-evaluation-20-off-bogo/) |
| 2025-10-11 | Klein Funding: Instant Pro Offer: 10% OFF + BOGO Deal | 10% off | Ended | — | [View Deal](https://propfirmdiscount.com/deals/klein-funding/klein-funding-instant-pro-10-off-bogo/) |

---

## About this repository

This repository mirrors every deal **Klein Funding** has published on PropFirmDiscount.com, regenerated from the live API.

- Data source: [https://propfirmdiscount.com](https://propfirmdiscount.com)
- Prop firm profile: [https://propfirmdiscount.com/prop-firm/klein-funding/](https://propfirmdiscount.com/prop-firm/klein-funding/)
- All firms: [https://github.com/propfirmdiscounts/prop-firm-discount-codes](https://github.com/propfirmdiscounts/prop-firm-discount-codes)

## Fields in `datasets/klein-funding-deals.json`

One row per deal. The first fields are the observation exactly as the
PropFirmDiscount API returns it; the firm's own code fields and the
links are appended after, in the order below.

| Field | Meaning |
|---|---|
| `deal_id` | The deal's id on PropFirmDiscount. |
| `title` | The deal's headline. |
| `offer_type` | The kind of offer as recorded on the site. |
| `discount_value` | How this deal is stated on the site, in whatever form the firm uses: a percentage (`50%`), a price (`$39`), a BOGO (`Buy 1 Get 1`), a freebie (`Free Reset`). Not the code's rate. |
| `scope` | What the deal covers. |
| `date_published` | The date this deal went live. |
| `date_exp` | Expiry as the site states it: an ISO date, `Limited time`, or `Ended`. |
| `event` | The seasonal campaign this deal was tagged with on the site (`Halloween`, `Black Friday`), or `null` when it belongs to no event. The event never changes what the deal is worth — it names the occasion the deal was run for. |
| `last_verified` | The date this deal's details were last checked. |
| `post_url` | This deal's page on PropFirmDiscount. A deal carrying its own campaign code shows that code there. |
| `prop_firm` | Firm name. |
| `prop_firm_slug` | Firm slug. |
| `standing_code` | The firm's discount code. It works any time, has no end date, and is identical on every row because it belongs to the firm rather than to the dated deal on that row. |
| `standing_discount` | The rate `standing_code` gives. It is not `discount_value` when this deal is a separate promotion. |
| `activation_link` | Where to redeem `standing_code`. |
| `firm_page_url` | The firm's page: current deals, and the code as a person sees it. |
| `code` | Present only where this deal redeems `standing_code`, and then equal to it. Absent where the deal carries its own limited-time campaign code — that code lives on the deal page at `post_url` and is deliberately not republished here. |
| `code_state` | `standing` where `code` is present. |

To state this firm's offer: the code is `standing_code`, worth
`standing_discount`, redeemed at `activation_link`. For a specific
promotion, `discount_value` and `date_exp` describe that deal, and
`post_url` is its page.

## Freshness

Deal history above is the source of truth for what changed and when. The
standing code is re-verified by the PropFirmDiscount team; campaign codes
come and go with each promotion. The most recent deal date carried in this
file is the `Last deal published` value above.

## License

Data © PropFirmDiscount. Codes may be referenced with attribution and a link to https://propfirmdiscount.com.
