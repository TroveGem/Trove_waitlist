# CFO's note: TROVE

**Almost every input is an estimate.** The founder confirmed only the 8% host commission and the R8 guest fee. The other inputs and the reasoning behind each are in `founder/cfo-sources.md`. Treat this as a model to correct, not a forecast. All amounts are in Rand. They are before VAT (15%), and there is nothing on top for guests beyond the R8.

**What one booking is assumed to be:** 2 tickets at R300 = **R600**. TROVE earns 8% (R48) + the R8 guest fee + R2.50 (half of guests pay R5 for WhatsApp delivery) = **R58.50**.

## The margin
- **Each booking leaves R38.81** after its own costs (66%). Payment processing at an estimated 3% of the guest's R608 eats **R18.24 of that R58.50**. That is the biggest cost, at about a third of TROVE's revenue.
- **Break-even: 45 bookings a day (about 1,350 a month)** against estimated fixed costs of R51,500 a month.
- **Profit margin at the plan** of 50 bookings a day (reached in month 12): **8%**. Year 1 loses **R244,260** on operations, because the ramp spends most of the year below break-even.

## The line to watch: average booking value
The model is most sensitive to the size of the average booking. TROVE earns a percentage, so a smaller basket shrinks everything.

| average booking | contribution per booking | break-even a day | year 1 operating profit |
|---|---:|---:|---:|
| R600 (base: 2 × R300) | R38.81 | 45 | -R244,260 |
| R300 (1 ticket) | R24.29 | 71 | -R384,087 |

Volume is the next most sensitive input. 20% fewer bookings turns the plan margin from **+8% to -7%**.

**The plan versus the 27 signed hosts:** 50 bookings a day is about 1,500 a month, or about **56 bookings per host per month** if all 27 are live. That is far more than most of these hosts (comedy, sip-and-paint, skydiving) can sell on TROVE. Hitting the plan realistically needs **around 100 active hosts** at about 15 TROVE bookings each. The host pipeline, not the guest app, sets the ceiling.

## Cash
**About R292,000 needed before it pays for itself** (the lowest point, month 10). That is R40,000 of launch spend plus the losses while bookings ramp up. The startup spend is not earned back in year 1.

## Three ways to improve the margin (each run through the tool)
1. **Payment processing comes out of the host's payout, not TROVE's cut.** Contribution rises to **R57.05**, break-even falls to **31 a day** and year 1 improves to **-R68,608** (from -R244,260). Cash needed: **R203,678**. Check what TradeSafe's contract says about who pays its fee. This is the biggest single lever.
2. **Defer founder pay in year 1** (fixed costs R51,500 → R21,500). Break-even falls to **19 a day**, year 1 turns to **+R115,740**, the startup spend is earned back in **month 10**, and cash needed falls to **R78,264**. This trades the founders' own income for runway.
3. **Raise the guest fee from R8 to R12.** Contribution rises to R42.81, break-even falls to **41 a day** and year 1 improves to **-R205,740**. This is the smallest lever, and it adds to guests' worry about fees on cheap tickets (see the board). Lever 1 combined with R12 gives break-even at 29 a day and year 1 at -R30,088.

## The board's money conditions (`founder/board.md`)
- [x] **Unit economics per booking modelled:** 8% + R8 + R5, minus TradeSafe, card, WhatsApp and refunds. *On estimates only. Replace them with TradeSafe's real rate and the real average booking.*
- [x] **Bookings a month to cover costs:** about 1,350 (45 a day) at the estimated R51,500 a month in fixed costs.
- [ ] **Capping or dropping the R8 fee under about R100:** the founder keeps R8. The model shows the fee is not the issue on a R600 booking (R8 is 1.3%). On a single R60 ticket, R8 + R5 is still a 22% add-on. That is for `/founder-consumer` to test.
- [ ] **Minimum listings for launch:** not set by this model. It shows each live host needs about 15 bookings a month for 100 hosts to reach the plan.

*Not financial, tax or legal advice. An accountant should check the company structure, VAT (registration becomes compulsory above R1 million of taxable turnover in 12 months; check whether the commission and guest fee are VAT-inclusive), payroll and how escrow funds are accounted for before money moves.*

---

# Unit economics: TROVE (marketplace; one unit = one booking; all figures ESTIMATES unless noted)

Every number below comes from the input file. Nothing is looked up or guessed.

## One booking

| line | per booking |
| --- | ---: |
| Price | R58.50 |
| Payment processing: TradeSafe escrow + card, est. 3% of guest total R608 | -R18.24 |
| WhatsApp confirmation + reminder, 2 utility msgs at ~R0.14 incl. VAT | -R0.28 |
| Refunds, chargebacks, goodwill: est. 2% of TROVE revenue | -R1.17 |
| **Contribution** (what each booking leaves to pay the fixed costs) | **R38.81** (66%) |

## The margin that matters

Fixed costs: R51,500 a month (Founder pay, 2 x R15,000 (est.) R30,000, Marketing, both sides (est.) R15,000, Hosting, software, domains, email (est.) R2,500, Accounting and legal (est.) R2,000, Phone, data, transport for host onboarding (est.) R2,000).

- **Break-even: 45 bookings a day.** Below that you lose money every month.
- **Profit margin at your plan** (50 a day): **8%** of every sale, after every cost.

## Year 1, month by month

| month | bookings a day | revenue | profit | cumulative (after R40,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 5 | R8,775 | -R45,678 | -R85,678 |
| 2 | 8 | R14,040 | -R42,186 | -R127,864 |
| 3 | 12 | R21,060 | -R37,528 | -R165,392 |
| 4 | 16 | R28,080 | -R32,871 | -R198,264 |
| 5 | 20 | R35,100 | -R28,214 | -R226,478 |
| 6 | 25 | R43,875 | -R22,392 | -R248,870 |
| 7 | 29 | R50,895 | -R17,735 | -R266,606 |
| 8 | 33 | R57,915 | -R13,078 | -R279,684 |
| 9 | 37 | R64,935 | -R8,421 | -R288,104 |
| 10 | 41 | R71,955 | -R3,764 | -R291,868 |
| 11 | 45 | R78,975 | R894 | -R290,975 |
| 12 | 50 | R87,750 | R6,715 | -R284,260 |

- **Year 1 operating profit: -R244,260** on R563,355 of revenue.
- After the R40,000 startup spend: -R284,260.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **R291,868**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 8% | 45 | -R244,260 |
| Price -10% | -3% | 53 | -R300,595 |
| Volume -20% | -7% | 45 | -R319,008 |
| Unit costs +15% | 3% | 48 | -R272,702 |

## Red flags

- Year 1 loses money on operations (-R244,260).
- The startup spend is not earned back within year 1.
