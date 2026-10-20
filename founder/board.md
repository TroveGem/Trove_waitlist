# Board summary: Trove

**Round 4 (after the founder's pricing and supply facts): 2 fund if, 1 pass. Average score 4.3 / 10. No change from round 3.**

| Lens | R1 (waitlist page) | R2 (+ demo) | R3 (+ website, Engine, live guest app) | R4 (+ 8% and 27 sign-ups) |
|---|---|---|---|---|
| Offers | 4 FUND IF | 4 FUND IF | 5 FUND IF | **5 FUND IF** |
| Monopoly | 3 PASS | 2 PASS | 3 PASS | **3 PASS** |
| Product | 4 FUND IF | 4 FUND IF | 5 FUND IF | **5 FUND IF** |

## Round 4: what the founder's facts changed

The founder confirmed that **hosts pay an 8% commission per booking**, and that **27 spots have signed up but none has created a profile or listing yet**. Each member found that the two facts cancel each other out.

**Better:**
- **The take now scales with the ticket price.** This fixes the round-3 "R8 needs huge volume" risk. Offers' gross take per booking for 8% + R8 (one ticket per booking, before TradeSafe fees and refunds):

  | Ticket | Take |
  |---|---|
  | R60 | R12.80 |
  | R150 | R20 |
  | R220 | R25.60 |
  | R1,450 | R124 |
  | R6,800 | R552 |

  At an assumed R150 average ticket, that is about 500 bookings a month for R10k and 5,000 for R100k, against 1,250 and 12,500 under R8 alone.
- **27 sign-ups show real interest from hosts**, which partly answers "how do the first hosts arrive?"

**Worse:**
- **The 8% contradicts every public page.** The Engine says "R0 to list" and "Start hosting free", the website promises "founding partner rates", and the Pricing link returns 404. Product: "A host first learns about the 8% from the payout, not the pitch." Monopoly: hosts who signed up expecting "free" will meet a charge.
- **None of the 27 has a listing, 11 days before launch.** That is interest, not commitment. Either onboarding from sign-up to live listing is broken or nobody has tried it yet (Product), and it is still not a dominated cell (Monopoly). Their categories and cities are unknown.

### Chair's note: follow-up facts (board not reconvened)

- **The R8 guest fee stays.** Round 4 already assumed this, so the numbers above stand. Offers' suggestion to cap or drop it under about R100 is still open for /founder-cfo and /founder-consumer.
- **The 27 are spread across categories and cities:** skydiving, events, sip-and-paint and comedy, in Johannesburg, Cape Town and Pretoria. This confirms the board's top risk ("too wide to win anywhere") rather than adding a new one. Two practical points:
  1. **Find the densest cell among the 27 and launch there.** The count per category and city decides which one, and that count is the most useful number you could give the board.
  2. **Cape Town hosts are signed up but Cape Town is not a launch city.** Decide what happens to them on 1 Nov (list them anyway, or give them a dated "coming soon"), and tell them before they find out from an empty city filter.

### Round 3 detail (still valid unless noted)

Reviewed: the waitlist page in this repo, the prototype (trove-1un.pages.dev), www.welovetrove.co.za, TROVE Engine (trove-engine.pages.dev, public pages and app code) and the production guest app (trove-your-next-adventure.pages.dev). The Engine was not tested while signed in.

## What round 3 settled

- **The venue side exists** and covers most of what the board asked for: a listing builder for ticket tiers, session slots and rooms; a QR door scanner on any phone; an audience CRM; team roles; analytics; per-event refund policies; and **TradeSafe escrow with ZAR payouts after the event**. All three members raised their view on this.
- **The production guest app shows no fake data.** Real sign-in and real bookings, and the made-up listings and social proof from the prototype are not shown.
- **The launch date is set:** 1 Nov 2026, Johannesburg and Pretoria.
- **The revenue model is defined:** free for hosts; guests pay an **R8 booking fee** (non-refundable if they cancel) plus an optional **R5 for WhatsApp ticket delivery**. The 3% / 8% host tiers survive only on the old waitlist page.

## Risks raised by more than one member (most dangerous first)

1. **Empty shelf on launch day** (all three). The live feed has **0 spots, 11 days before launch**, and no numbers are shared for signed hosts or ready listings. Product: "A beautiful app with 0 spots is the worst first five minutes possible."
2. **Still too wide** (all three). Four host types (events, experiences, stays, venues), plus promoters and artists, and 11 city filters, for a two-city launch. "Stays" is new and doesn't fit "Decide. Book. Show up."
3. **The R8 flat fee** (all three, from different angles; *largely resolved in round 4 by the 8% commission; the founder confirms the R8 guest fee stays*):
   - *Offers:* gross R8 needs about 1,250 paid bookings a month for R10k and about 12,500 for R100k. A 3% take beats R8 only on tickets above about R267. So R8 suits cheap, frequent nights but gives away value on high-priced items (0.12% of a R6,800 retreat). If TradeSafe's fee comes out of the R8, the margin per booking could be close to zero.
   - *Monopoly:* free hosting plus a flat fee creates no lock-in, and a rival can undercut it overnight.
   - *Product:* R8 + R5 on a R60 ticket is a 22% add-on, and it contradicts the "no booking fees" promise.
4. **The fee story contradicts itself** (Product, Offers). "Is it free for seekers? Yes, 100% free. No booking fees." (waitlist page) vs. R8 in production. A WhatsApp-native brand charging R5 for WhatsApp delivery. The host "Pricing" link returns 404.
5. **No distribution numbers and no moat yet** (Monopoly, Offers). The CRM is the only candidate for switching costs, and that is unproven.

### Where the board disagrees
- **Monopoly still says PASS** (up 2→3 because the supply-side tooling exists). Its view: a built product is not a dominated market, and free plus R8 is the cheapest price, not a wedge. It wants proof of a concentrated cell, of hosts still using the CRM after 30 days, and of seekers booking again.
- **Offers and Product say FUND IF** (both 4→5). The hard engineering is done; what's left is a launch-focus problem plus fee economics that can be fixed.
- **On the R8 fee:** Offers wants a fee that scales with ticket price above a threshold. Product mainly wants it shown honestly, and asks whether WhatsApp delivery should be free. Monopoly questions whether any guest fee survives a competitor that charges none.

## Conditions (checklist for the rest of the pack)

**Before 1 Nov (10 days):**
- [ ] **Onboard the 27 signed spots personally (set up their listings for them), and tell them the 8% in writing first**, plus any founding-partner discount with an end date. Report how many go live and where the rest stalled (all three; Monopoly wants at least half live *after* hearing the 8%).
- [ ] **Publish the pricing:** a working Pricing page stating 8%, and retire "R0 to list" / "Start hosting free" / "no booking fees" (all three).
- [ ] **Have a screenful of real, bookable spots live before opening to guests**, concentrated in one category in one city (all three; Offers suggests 20–30 as a placeholder for /founder-cfo to set). If it isn't there, delay the guest launch rather than open an empty app.
- [ ] **Hide what has no stock:** empty city filters, unused categories and "Stays" until real supply exists (Product, Monopoly).
- [ ] **Make the fee story consistent:** show R8 upfront, retire "no booking fees" / "Service fee: Free" copy (including this repo's waitlist page), fix the 404 Pricing link, and decide on free WhatsApp delivery (Product, Offers).
- [ ] **Remove the old demo listing module** (real brand names, generated follower counts) from the production bundle (Offers, Product).

**Numbers to establish:**
- [ ] **Unit economics per booking:** 8% + R8 (+R5) minus TradeSafe fees, WhatsApp message cost and refunds; bookings a month to cover running costs; and whether to drop or cap the R8 guest fee on tickets under ~R100 (Offers). *(/founder-cfo)*
- [ ] **Guest acceptance of R8 (+R5)** on cheap tickets vs. buying directly or elsewhere. *(/founder-consumer)*
- [ ] **What hosts use and pay today** for ticketing, reservations and door management in JHB/PTA, and whether "free to list" is a real difference. *(/founder-competitors)*

**First 30 days:**
- [ ] **20+ real bookings end to end** (book → scan at door → payout → one refund), with the failure rate at each handoff (Product, Offers).
- [ ] **Publish real proof:** bookings, check-in rates, no-shows. These replace the unsourced "60% fewer no-shows" claim (Offers).
- [ ] **Show a share of supply** in the launch area, **CRM use by hosts after 30 days**, and **seekers booking again** (Monopoly's conditions for reopening its vote).
- [ ] **A founding-host guarantee** with real urgency, e.g. "we fill N seats or promote you free". *(/founder-offer)*

## The strongest version the board can see

Trove has done the hard part. It has built both sides of the marketplace, with escrowed payments and a door scanner, ahead of launch. The risk now is the launch itself. The strongest version opens on 1 Nov in **one category in Johannesburg**, with a full screen of real, bookable listings from hosts who are actively using the Engine. Every other host type, city and "Stays" stays hidden until it has stock. Its pricing is the same everywhere and the guest sees it upfront, and the R8 has been checked against TradeSafe's fees. Measure the first 30 days (bookings, check-ins, payouts, repeat guests, hosts returning to the CRM) and publish them. That turns Offers' "likelihood" problem into evidence and gives Monopoly the concentrated market it is waiting for. Opening an empty app across four host types would waste a well-built product.
