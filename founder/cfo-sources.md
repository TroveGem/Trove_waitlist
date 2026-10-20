# Where the CFO numbers come from

Labels: **confirmed** (founder said so), **public** (a public source, linked), **estimate** (my reasoning; replace it with real numbers).

## Revenue per booking: R58.50
| input | value | label | reasoning |
|---|---|---|---|
| Host commission | 8% of booking value | **confirmed** | Founder, 2026-10-20 |
| Guest booking fee | R8 per booking | **confirmed** | Founder, and the production checkout code |
| WhatsApp delivery | R5, optional | **public** (production app code) | Assumed 50% of guests choose it → R2.50 per booking (**estimate**) |
| Average ticket | R300 | **estimate** | The 27 signed hosts range from comedy (~R100–R200) and sip-and-paint (~R300–R400) to skydiving (~R3,000). The prices in the old demo listings were similar. Skydiving is rarer, so it is weighted down. |
| Tickets per booking | 2 | **estimate** | Going out is mostly done in pairs or groups. The app has split-the-bill and group features. |
| Booking value | R600 | **estimate** | 2 × R300 |

## Variable cost per booking: R19.69
| input | value | label | reasoning |
|---|---|---|---|
| Payment processing (TradeSafe escrow + card) | 3% of R608 = R18.24 | **estimate** | TradeSafe has quoted 1.5% flat on its API ([Ventureburn, 2018](https://ventureburn.com/2018/02/goodbye-online-crooks-sa-fintech-startup-keeps-money-safe-till-buyers-sellers-agree/); [FA News](https://www.fanews.co.za/article/technology/41/general/1204/goodbye-to-online-crooks-sa-fintech-startup-keeps-money-safe-till-buyers-and-sellers-both-agree/23756)). That figure is old, and card acquiring usually costs extra, so 3% in total. Assumes TROVE pays all of it. **Replace with the contract rate.** |
| WhatsApp messages | 2 × ~R0.14 = R0.28 | **public** + estimate | Meta began per-message charging on 1 Oct 2026. The utility rate for SA is about US$0.0076 (≈R0.12) plus 15% VAT ([Briefly](https://briefly.co.za/people/250520-meta-charge-whatsapp-business-api-users-message-1-october-2026/), [ChatMaxima](https://chatmaxima.com/whatsapp-api-pricing/south-africa/)). Sources disagree on charges within the 24-hour window. Verify against [Meta's rate card](https://developers.facebook.com/documentation/business-messaging/whatsapp/pricing). Two messages (confirmation and reminder) are an **estimate**. |
| Refunds, chargebacks, goodwill | 2% of R58.50 = R1.17 | **estimate** | Host-cancelled events refund the full amount including the R8. Guest cancellations keep the R8. |

## Fixed costs: R51,500 a month (all **estimates**)
| line | R/month | reasoning |
|---|---:|---|
| Founder pay | 30,000 | 2 founders × R15,000, a modest living wage. Set to 0 if unpaid. |
| Marketing | 15,000 | Social ads and content for guests, plus host outreach in JHB/PTA. |
| Hosting and software | 2,500 | Supabase, Cloudflare Pages, domains, email, design tools. Small at this scale. |
| Accounting and legal | 2,000 | Bookkeeping, plus occasional legal work on T&Cs and refunds. |
| Phone, data, transport | 2,000 | Visiting hosts to onboard them. |

## Startup: R40,000 (all **estimates**)
The build is treated as already done (sunk). Remaining before launch: launch marketing R20,000; legal (T&Cs, POPIA, refund policy, company admin) R10,000; listing photos and content R5,000; contingency R5,000.

## Volume (all **estimates**)
- Plan: 50 bookings a day (about 1,500 a month) by month 12.
- Ramp (bookings a day by month): 5, 8, 12, 16, 20, 25, 29, 33, 37, 41, 45, 50.
- Month 1 is 5 a day (about 150 bookings) across the 27 signed hosts, if most go live. That is about 5–6 bookings per host in month 1.
- No consumer panel has run yet (`founder/panel/results.md` does not exist), so the ramp has not been checked against simulated buy rates. Run `/founder-consumer` to test it.
