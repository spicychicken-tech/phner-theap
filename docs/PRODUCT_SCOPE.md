# Phner Theap MVP Scope and What We Leave Out

**Task:** PT-004, Write requirements and user stories  
**Project:** Phner Theap  
**Course:** IT Project Management (I5, 2026–2027 Semester 1)  
**Team:** Spicy Chicken, Final Year Project Team  
**Document date:** 2026-11-26  
**Status:** Draft  
**Plan:** [`../plan.md`](../plan.md), v1.0  
**Needs first:** PT-001 (kick-off meeting)

## 1. Scope decision

The **minimum viable product (MVP)** of Phner Theap is a **web platform with two sites**: a main site for Host and Guest, and a separate admin site. A Host picks a template, edits it, adds guests, shares the invitation by link or QR code, and can pay and print it. A Guest opens the invitation without an account, replies and sends a wish. An Admin manages the content and the orders.

A good MVP is a **complete flow from start to end that really works**, not a site with many half-finished pages. The core flow is: **sign in → pick a template → edit and save → add guests → share the link or QR → guest replies → host sees the replies**.

Everything listed as included below is a **plan**, not a claim that it is built.

## 2. In scope (must have)

| ID | Feature | What we can see when it works | Main owner area | Tasks |
| --- | --- | --- | --- | --- |
| M01 | Two sites and one database | Main site and admin site run, and both use one MongoDB database | Setup and database | PT-002, PT-003, PT-005, PT-006 |
| M02 | Accounts | A Host can sign up, sign in, reset the password and sign out. Admin signs in on the admin site. Pages are protected by role | Authentication | PT-009, PT-017 |
| M03 | Templates | Templates for every event and a modern minimalist style can be listed, previewed, searched and filtered | Templates | PT-012, PT-013, PT-019, PT-030, PT-052 to PT-056 |
| M04 | Editor and invitation | A Host creates an invitation, edits canvas, text and colours, uploads photos, and saves a draft, publishes or unpublishes it | Editor and backend | PT-021, PT-026, PT-027, PT-028, PT-031 |
| M05 | Languages and events | The invitation can be in English or Khmer and can have several events with a programme | Content | PT-024, PT-033, PT-035 |
| M06 | Map and location | The guest sees the place on a map with directions | Templates and map | PT-029 |
| M07 | Guests and sharing | A Host adds guests, and shares by link or QR, with a personal link and QR for each guest | Guests | PT-014, PT-032, PT-036, PT-041 |
| M08 | RSVP and wishes | A guest replies and sends a wish. The host sees totals, who opened, and meals | Guests | PT-043, PT-051 |
| M09 | Gift QR | A Host adds a gift QR code and the guest can see it | Payment | PT-042 |
| M10 | Reminders and alert emails | A Host schedules reminders and gets an email when a guest replies and the day before the event | Backend | PT-040 |
| M11 | Cart, payment and plans | A Host can pay, and can choose a free plan, a subscription or a one-time payment. Admin manages plans and orders | Payment | PT-038, PT-044, PT-047, PT-050 |
| M12 | Download and print | A Host can download the invitation as a PDF or image to print it as a card | Print | PT-049 |
| M13 | Host pages | Dashboard, my invitations, profile, wishlist and settings work with real data | Host site | PT-010, PT-011, PT-020, PT-034, PT-039, PT-048 |
| M14 | Admin pages | Admin manages hosts, categories, event types, template styles, invitations and sees an overview | Admin site | PT-008, PT-018, PT-023, PT-025, PT-037, PT-045, PT-046 |
| M15 | Public pages | Guests can see the home page, featured templates and the invitation page | Guest site | PT-015, PT-016, PT-022 |

## 2.1 Details we add to the must-haves

These details come from the team's requirements document and make the must-haves above clear. They are not extra tasks.

**Ceremony types (M03).** Main types: wedding, engagement, birthday, graduation, house blessing, monk ordination, Khmer New Year, memorial. More types to be confirmed: anniversary, baby celebration, corporate or opening event, merit-making, general event. Every template has a language tag (Khmer, English or bilingual) and the host can filter by it. Admin can add, rename, hide and reorder categories without code. Khmer fonts must show correctly in the editor, preview and download.

**Minimalist style (M03).** Few colours (at most three) on a neutral background, clear text order (names, date, venue, details), simple lines or shapes, and readable on a phone without zooming. At least wedding, engagement, birthday and graduation have one.

**Plans (M11).**

| Plan | Meaning |
|---|---|
| Free | No payment. Basic templates and limited features. Every new account starts here |
| Subscription | Pay a fixed fee for a month or a year. Premium features and templates for all invitations in that time. The host renews by hand, with a reminder email |
| One-time | Pay once for one invitation. Premium features for that invitation only |

Plan limits (for example number of invitations, premium templates, watermark, high-resolution download) are set by Admin and can change without code. When a subscription ends, invitations and data are kept, premium features lock, and published invitations stay viewable for a grace period (length to be confirmed). Plan rules are checked on the server, not only on the screen.

**Alert emails (M10).** Emails go in the user's language, Khmer or English. They are queued, retried when they fail, and never sent twice for the same event. The kinds we build: guest replied, event reminder, invitation changed (date, time or place), thank-you, payment receipt, and a plan that is about to end or has ended. Essential emails (password reset, receipt) cannot be turned off. Optional emails can be turned off, with an unsubscribe link.

## 3. Guest and screens

A **guest** has no account. They only use the invitation link or QR code. The exact pages and screens are decided in the Figma prototype (PT-007) and the requirements (PT-004). This document sets the **scope**, not the design of each screen.

## 4. Not in scope

These features are **not promised** in the MVP. We do not plan or build them without an approved change.

| Left out | Why |
| --- | --- |
| Ecommerce and vendors | Not needed for the main flow |
| Venue rental | Not needed for the main flow |
| Cameraman booking | Not needed for the main flow |
| Earn money by creating templates | Needs designer accounts and payouts |
| Sharing by Telegram | Not enough time |
| Co-hosts, seating plan, check-in at the event | Not enough time |
| Live location, support tickets, audit log, reports | Not enough time |

**Also not promised:** mobile apps, more languages than Khmer and English, and payment methods other than the ones we choose in the cart task. They can be future work.

## 5. Quality and limits

- **Platform:** a website that works on a modern phone and a computer browser. No mobile app.
- **Speed:** pages should feel fast on our test computers. We record what we see. We do not promise a number.
- **Easy to use:** a first-time guest can open the invitation, reply and find the map without help.
- **Reliable:** no broken link, no broken sign in, and no step that needs a developer tool.
- **Khmer:** Khmer text shows correctly on screen and in the downloaded PDF or image.
- **Security:** passwords are stored safely, and pages are protected by role.
- **Assets:** we write down the source and license of every template, font and image.
- **Documents:** a README with how to run the project, and an accurate final report.

## 6. Checkpoints

The milestone dates are in [plan.md](../plan.md). For each checkpoint we show a working page, a test result or a recording. A ticked box alone is not proof.

## 7. How we change the scope

1. Write the change in a GitHub Issue: **what feature, why, who, which task IDs, how many extra days, and what it does to the schedule**.
2. Say what kind of change it is: a **bug fix** (not new scope), a **clarification**, or **new scope**.
3. The team checks it against our 39 working days each, the sprint plan, the risks and the 19 January freeze.
4. We agree as a team, and ask the teacher if the course needs it. We write the decision down.
5. Only then we update `plan.md`, the issues, and the GIC ITC website, so all three say the same thing.

**If we are late:** keep the main flow working first (sign in, template, editor, save, share, guest reply). Cut polish before we cut a must-have. Removing a must-have (M01 to M15) needs a clear team decision. We do not quietly call it optional.

## 8. Checklist for PT-004

- [ ] The MVP and the must-have features (M01 to M15) are clearly written.
- [ ] Left-out features are clearly written.
- [ ] We agree what "guest" means (no account).
- [ ] The scope is checked against `plan.md`.
- [ ] The team talked about whether we can finish, and the decision is written.
- [ ] The final scope is linked from a GitHub Issue or meeting note, and the GIC ITC plan is updated if needed.

**When is PT-004 done:** when the scope and the left-out list are written, and the team has reviewed and accepted them. Approving this document does not mean the features are built.

## 9. Open questions for the client

| No. | Question | About |
|---|---|---|
| 1 | Which extra ceremony types are needed, and how many templates per type at launch? | Templates |
| 2 | Does "one-time paid" mean one payment per invitation, or one payment for lifetime use? | Plans |
| 3 | Should a subscription renew automatically? Not included for now | Plans |
| 4 | What are the prices, plan limits and the grace period after a plan ends? | Plans |
| 5 | Which other emails are needed, and at what times? Which email service do we use? | Alert emails |
| 6 | Which payment method do we use for plans and orders? | Payment |

## 10. Revision history

| Date | Version | What changed |
| --- | --- | --- |
| 2026-11-26 | Draft v0.1 | First version of the scope, from plan.md v1.0 |
| 2026-11-27 | Draft v0.2 | Added details from the requirements document (ceremony types, plans, alert emails) and open questions |
