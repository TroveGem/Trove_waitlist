# Board brief: Trove

Source: the founder's public waitlist page (the only material available). Nothing below is the chair's opinion.

## The idea
- What it is: a two-sided marketplace in South Africa where people discover and instantly book entertainment venues and experiences, and venues manage bookings, guest messages and payouts.
- Who it is for: two sides. Venues: nightclubs, bars, comedy clubs, adventure/activity operators, event spaces and restaurants. Experience-seekers: people aged 21-35 who go out regularly.
- What it sells, at what price: free for seekers (no booking fees). Venues pay a commission per successful booking: Starter 3% (unlimited listings, basic analytics, WhatsApp notifications), Professional 8% (adds advanced analytics, weekly featured placement, marketing campaigns, priority support), Enterprise custom (venue groups: white-label, API, dedicated manager). No upfront or monthly fees on Starter.
- Where and how: mobile-first app/platform, launching in Johannesburg, Cape Town and Durban (Pretoria and "Other" collected on the waitlist). Seekers browse by location/type/mood, book in seconds, get a WhatsApp confirmation, show a digital ticket at the door, then review/share for rewards. Venues get weekly Monday payouts to SA banks.
- Budget and constraints: not stated (unknown). Team size and skills not stated. The waitlist page announced a Q2 2026 launch; as of 2026-10-20 that date has passed and the current launch status is not stated.

## What the waitlist page promises

**Positioning:** "South Africa's New Home for Entertainment" / "South Africa's premier entertainment marketplace". Company name on the page: Trove Technologies, made in Johannesburg.

**To venues:**
- Zero-effort booking management: automated reservations, instant confirmations, capacity management, no double-bookings.
- Built-in marketing engine: featured placements and algorithmic recommendations to active users.
- WhatsApp-native communication: automated confirmations, reminders, two-way guest messaging. Claim on page: "Reduce no-shows by 60% with WhatsApp reminders" (no source given).
- Revenue intelligence: booking trends, peak hours, customer demographics.
- Weekly payouts to all major SA banks, "no holding periods, no hidden fees".
- Mobile-first management; multi-location dashboard.
- Fill empty seats in off-peak hours; access to seekers aged 21-35; pay only when you earn.

**To seekers:**
- Discover curated, "undiscoverable" spots (underground comedy, hidden rooftops), "curated by locals, for locals".
- Real-time availability, book in ~30 seconds.
- Social: see where friends are going.
- Member-only pricing, early-bird specials, VIP packages; rewards on every booking.
- Every venue vetted for quality and safety.
- Flexible cancellation: most bookings free to cancel up to 24h before.
- One app for nightlife, comedy, adventure and events; split bills with friends; last-minute availability finder; personalised recommendations.

**Waitlist mechanics:** venue form collects name, venue name, city, venue type, email, WhatsApp number, estimated monthly bookings (0-50 / 50-200 / 200-500 / 500+). Seeker form collects name, email, WhatsApp, city, favourite experience type, how often they go out. Earlier sign-ups get priority; referring a friend moves you up 10 spots. The page shows live waitlist counters but the actual numbers are not in the brief (unknown).

## Unknowns (not provided by the founder)
- Budget, funding, runway, team size and skills.
- Waitlist size on either side.
- Average booking value, booking volume, or how a "booking" is priced for venues that do not currently charge for entry or reservations (e.g. free-entry bars, restaurants).
- Customer acquisition cost on either side.
- Named competitors and market size (to be researched by /founder-competitors; do not assume).
- Current launch status: the page announced Q2 2026; today is 2026-10-20.

## Update 2026-10-20: the working demo (https://trove-1un.pages.dev)

The founder shared a live clickable demo. What it actually contains (observed directly; nothing below is the chair's opinion). The company website, www.welovetrove.co.za, could not be reached and has not been reviewed.

**What it is today:** a polished, mobile-first, seeker-only consumer app (dark theme, PWA). Tagline: "Decide. Book. Show up." Positioning line: "Nightlife, food, music, adventure, wellness, arts, family & community — sorted in 30 seconds." Social/OG copy: "Discover and book South Africa's best nightlife, comedy and adventures in seconds."

**Scope shown:** 40 listings ("spots") across 9 categories (Nightlife, Food & Drink, Music, Adventure, Wellness, Arts & Culture, Family & Social, Community) and 10 city filters (Joburg, Pretoria, Sandton, Soweto, Cape Town, Stellenbosch, Durban, Gqeberha, Bloemfontein, Polokwane). This is wider than the waitlist page (6 venue types, 3 launch cities).

**Every listing is a dated, priced item**, i.e. the demo treats a "booking" as a ticket for a specific date/time. Examples and prices shown: warehouse techno night R150, rooftop sunset session R220, comedy open mic R90, karaoke R60, jazz room R200, speakeasy R280, brunch R240, bunny chow R95, fine-dining tasting menu R1,850, wine-farm 8-course R1,450, live music R350, jazz festival R950, music festivals R1,450-R1,850, tandem paraglide R1,450, bungee R1,750, skydive R2,950, 2-day hike R2,200, spa day R3,200, wellness retreat R6,800, museum late R180, Comic Con R320, theme park R290, aquarium R320. Some listings are "Free" (markets), which earn no commission.

**Listings mix invented venues with real, named South African businesses and events**, e.g. Marble (with its chef named), The Saxon spa, Zeitz MOCAA, Bassline, Cape Town Jazz Festival / espAfrika, Rocking the Daisies, Ultra South Africa, Comic Con Africa / Reed Exhibitions, Gold Reef City, uShaka Marine World, Constitution Hill, Bloukrans Bungy / Face Adrenalin, SANParks; some host pages include real-looking contact emails. Nothing in the demo says whether any of these businesses are partners. Ratings, review counts, follower counts, "live capacity" bars (e.g. "178/200 · 89%"), "Almost Full / Filling Up" badges, and "3 from your community going" are all hard-coded demo data.

**Screens and flows present:**
- Discover feed with tabs For You / With Friends / Trending, story-style "LIVE" bubbles, Editor's Picks, category and city filters.
- Search with sort: Trending, Closest, Cheapest, Top Rated.
- Spot page: rating, distance, date/time, live capacity bar, about, tags, "Your crew is going" social block with Invite, hours, host link, address with Directions, "Split the bill — share the cost with your crew", quantity picker, Book now.
- Host (venue) profile page: bio, followers, events, "Join community", amenities, hours, upcoming events, phone/email/Instagram.
- Checkout: 3 steps (Details, Payment, Confirm). Collects name, email, WhatsApp number; "We'll send your QR ticket to email and WhatsApp." Shows "Service fee: Free". Payment methods Card and Instant EFT. Payment is simulated ("Test mode · Use card ending 0000 to simulate a failure"); no booking is stored on a server.
- My Tickets, Saved (wishlist), Profile (WhatsApp updates toggle, push notifications, "Refer a friend — Earn R50 when they book", reviews, friends).
- A "Host +" bubble exists and the backend has user profiles with an "is host" flag, but **there is no venue-side product in the demo**: no venue dashboard, listing creation, availability management, door scanning, analytics, or payouts.

**What the demo does not show:** any real venue partner, any real transaction, any payment provider integration, any commission or venue pricing, any WhatsApp integration (only copy promising it), or traction numbers.

## Update 2026-10-20: the company website (https://www.welovetrove.co.za)

Observed directly. Three pages: home (`/`), hosts (`/partners`), guest sign-up (`/notify`).

- **Launch date:** a countdown to **1 November 2026, 00:00 SAST** (11 days from today). Title: "TROVE | Launching Soon".
- **Launch cities: Johannesburg and Pretoria** ("get on the TROVE partner list before we open in Johannesburg and Pretoria"). This is narrower than the waitlist page (3 cities) and the demo (10 city filters).
- **Positioning:** "Events, experiences and stays across South Africa, all in one app. Find your next night out and book it in seconds." It lists four pillars: Events (gigs, comedy, festivals, club nights), Experiences (tastings, tours, adventures), **Stays** ("somewhere good to sleep after the night out", which is new and not in the demo) and Community (see where friends are going).
- **For hosts (/partners), "TROVE FOR HOSTS — Turn your space into a destination":** "Founding partner rates: lock in launch pricing on every ticket and booking." "One dashboard: listings, tickets, guest lists and payouts in a single place." "Reach the right crowd." "We'll set your profile up with you." The sign-up takes under a minute and asks for no payment details. Partner types: Venue, Promoter, Experience host, Stay/accommodation, Artist/performer. City options: Johannesburg, Pretoria, Cape Town, Durban, Gqeberha, Elsewhere. **The site states no commission rates.** The 3% / 8% tiers appear only on the older waitlist page.
- **For guests (/notify):** an email-only sign-up. "Rooftops, comedy, club nights, adventure — one tap away."
- **Socials:** Instagram, TikTok, LinkedIn and WhatsApp, all under @welovetrove. Forms are backed by Supabase.
- **Other apps linked from the site's code (not reviewed, because they were unreachable from this session):** `trove-engine.pages.dev`, with a sign-up link, which appears to be the host/venue-side "engine"; and `trove-your-next-adventure.pages.dev`, a seeker app. Whether a venue-side product exists is therefore **unconfirmed**, not absent.
- No traction numbers, partner names or team information on the site.

## Update 2026-10-20 (later): the production apps

Observed directly. These change several earlier "unknowns". **Where they conflict with the demo section above, this section is current.** The demo at trove-1un.pages.dev is an older prototype.

### TROVE Engine, the host/venue platform (https://trove-engine.pages.dev)
- **Exists and is built out.** Marketing page: "Where South Africa's Spots grow. List events, experiences, stays or your venue on TROVE. Guests discover you, book and pay in Rands." Calls to action: "Start hosting free" (sign-up) and "Talk to partnerships" (enquiry form for festivals, multi-venue programmes and brand partnerships, with dedicated plans).
- **Four host types:** event organisers (ticket tiers, live entry control), experience providers (sessions, capacity), accommodation hosts (rooms, stays), venue operators.
- **Signed-in app routes found in its code:** dashboard, listings (create and edit, with ticket tiers, session slots, rooms), calendar, slots, bookings, **door scanner** (QR, any phone, live check-in counts), audience CRM (followers, past guests, regulars, per-guest page), team and roles (staff invites), live analytics, reviews, **payouts**, notifications, support tickets, onboarding with verification status, settings. Not tested while signed in.
- **Payments:** "Card payments are held in escrow by **TradeSafe**. Payouts land in your South African bank account once your guests have been, and refunds are handled for you." Headline figures: "R0 to list your Spot", "ZAR every payout", "TradeSafe escrow-secured payments".
- **Refund policies chosen by the host per event:** TROVE standard (90% back 72h+ before, 50% at 24–72h, nothing under 24h), 7 days' notice, 30 days' notice, or no refunds. If the host cancels, every guest gets a full refund.
- **WhatsApp:** booking notifications to guests on WhatsApp.
- The footer "Pricing" link goes to welovetrove.co.za/pricing, which returns **404**. No page states a commission or fee for hosts.

### Revenue model, from the production code
- **Guests pay a TROVE booking fee of R8 per booking.** It is non-refundable when a guest cancels and refunded if the host cancels. The amount is served from the backend, and the host-facing copy states "R8".
- **An optional R5 "WhatsApp delivery" charge** applies if the guest chooses to receive the QR ticket by WhatsApp instead of email.
- **Listing is free for hosts.** No host commission appears anywhere in the production apps. The 3% / 8% tiers exist only on the old waitlist page in this repo.
- Unknown: TradeSafe's fees and who bears them; whether any host-side take exists in practice. *(/founder-cfo)*

### Guest app, production (https://trove-your-next-adventure.pages.dev; build 2026-10-20)
- Same design as the demo, with real auth (sign-in, onboarding "Tonight lives here.") and real backend bookings with ticket codes and refunds. Tabs: Discover (For You / With Friends / Trending), Search, **Spark** (friends, groups, split ticket payments; sign-in required), Tickets, Profile, Saved, Support, Notifications.
- **Live inventory today: 0 spots** in the feed and search. City filters: 11 cities (Joburg, Pretoria, Cape Town, Stellenbosch, Durban, Gqeberha, Bloemfontein, Polokwane, Knysna, East London).
- **No fabricated listings or social proof are visible in production.** The bundle still ships the old demo listing file (real brand names, generated follower counts) as a lazily loaded module, but the live feed did not show it.
- Checkout: tickets, the booking fee, optional WhatsApp delivery, ticket by WhatsApp or email.

### Launch facts (from the website, repeated)
Launch on **1 Nov 2026** in **Johannesburg and Pretoria**, 11 days from today. Host and guest sign-up lists exist. **No numbers have been shared** for signed hosts, listings ready to publish, or sign-ups.

## Update 2026-10-20 (founder-confirmed facts)

Stated directly by the founder; these supersede earlier unknowns:
- **Host pricing: TROVE charges hosts an 8% commission per booking.** This is in addition to what production shows guests (an R8 non-refundable booking fee and an optional R5 WhatsApp delivery). The founder has not said whether the R8 guest fee stays at launch. The 8% is not stated on any public page reviewed: the Engine says "R0 to list" / "Start hosting free", the website promises "founding partner rates", and the Pricing link returns 404. The 3% Starter tier on the old waitlist page is no longer current.
- **Supply: 27 spots have signed up** but **have not yet created their profiles or listings** in the Engine. The founder has not said which categories or cities they are in, or how many will have bookable listings live by 1 Nov.
- **The R8 guest booking fee stays** (founder-confirmed). Total take per booking = 8% of the booking from the host + R8 from the guest (+ optional R5 WhatsApp delivery).
- **The 27 signed spots are spread across categories and cities** (founder-confirmed): for example skydiving, events, sip-and-paint and comedy shows, in Johannesburg, Cape Town and Pretoria. The exact count per category and city is not stated. Cape Town is not one of the announced 1 Nov launch cities (Johannesburg and Pretoria).
- **The waitlist page in this repo (index.html) is retired.** The founder has created a different waitlist, which has not been reviewed. Ignore the old page's copy (3%/8% tiers, "no booking fees", Q2 2026 launch) as a source of current facts.
