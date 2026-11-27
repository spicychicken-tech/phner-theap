# Project plan: Phner Theap

Team Spicy Chicken · Final Year Project Team · IT Project Management (I5, 2026-2027 Semester 1)

Keep this file in the repository and update task status each week. The GIC ITC website keeps its own imported plan and is the course progress-check source. After importing, keep the website and this file the same.

**Version:** v1.0 · **Official start:** 2026-11-26 · **Final delivery:** 2027-01-22.

**Product:** A web platform for designing and sharing digital invitations, with a main site for Host and Guest and a separate admin site. Built with Next.js and one MongoDB database. What is in and out of scope is in [docs/PRODUCT_SCOPE.md](docs/PRODUCT_SCOPE.md).

**Scrum model:** Sprint 0 (Start + Design, one week) and seven one-week sprints. Five members each have about 39 working days. The estimates are **1552 task-hours** (8 hours a day, a task with two or more owners counts for each owner) and **280 provisional Story Points**. Story Points are relative size, not hours.

**Import note:** The 56 task lines below follow the instructor's one-line Markdown syntax. The estimation and acceptance register at the end is a manual reference and may not fill the website's Points, Notes or dependency fields. Set First day to 11/26/2026 and Weeks per sprint to 1, and check the import preview before replacing the plan.

## Team

| Member | Role |
|---|---|
| PHE RITHIKA | Full-Stack Lead: project setup, sign in and sign up, template editor, cart and payment, admin sign in and orders |
| SAN MEYHIENG | Backend Developer: saving invitations, guests, RSVP, profile, host dashboard |
| SAR VICHADA | Web and QA Testing: invitation form and preview, admin hosts and invitations, admin overview, download and print |
| SOENG PRAKBORMEY | Database and Backend: database design, home page and invitation page, Khmer content, reminders and alert emails, wishes |
| SOK KIMHENG | Full-Stack Developer: templates, map location, personal and gift QR codes, plans, filters |

## Milestones

| Milestone | Date |
|---|---|
| Start and Design finished | 2026-12-02 |
| Sprint 2 review: sign in and sample pages for all 3 roles | 2026-12-16 |
| Sprint 4 review: invitations can be made, saved and opened by guests | 2026-12-31 |
| Sprint 5 review: guests, RSVP, payment and alert emails work | 2027-01-11 |
| Sprint 6 review: real data, plans, download and print | 2027-01-18 |
| Feature freeze (no new features) | 2027-01-19 |
| Final delivery | 2027-01-22 |

## 1. Start (week 1, 2026-11-26 to 2026-12-02)

- [ ] PT-001: Kick-off meeting · 2026-11-26 to 2026-11-26 · PHE RITHIKA, SAN MEYHIENG, SAR VICHADA, SOENG PRAKBORMEY, SOK KIMHENG
- [ ] PT-002: Project structure: main site, admin site, shared database code · 2026-11-27 to 2026-12-01 · PHE RITHIKA
- [ ] PT-003: Create GitHub repository · 2026-11-27 to 2026-11-27 · PHE RITHIKA
- [ ] PT-004: Write requirements and user stories · 2026-11-27 to 2026-11-27 · SAN MEYHIENG, SAR VICHADA, SOK KIMHENG

## 2. Design (week 1, 2026-11-30 to 2026-12-02)

- [ ] PT-005: Design database: Admin · 2026-11-30 to 2026-12-01 · SOENG PRAKBORMEY, SOK KIMHENG
- [ ] PT-006: Design database: Host and Guest · 2026-11-30 to 2026-12-01 · SAN MEYHIENG, SAR VICHADA
- [ ] PT-007: Design prototype templates · 2026-12-02 to 2026-12-02 · SAN MEYHIENG, SAR VICHADA, SOENG PRAKBORMEY, SOK KIMHENG

- [ ] **Milestone: Start and Design finished** · 2026-12-02

## 3. Sprint 1 (week 2, 2026-12-03 to 2026-12-09)

- [ ] PT-008: Admin: Categories · 2026-12-03 to 2026-12-04 · SAN MEYHIENG
- [ ] PT-009: Host and Guest: Authentication (sign in, sign up, forgot password, renew password, sign out) · 2026-12-03 to 2026-12-09 · PHE RITHIKA
- [ ] PT-010: Host: Dashboard and my invitations · 2026-12-03 to 2026-12-04 · SAR VICHADA
- [ ] PT-011: Host: Invitation preview · 2026-12-07 to 2026-12-09 · SAR VICHADA
- [ ] PT-012: Host: Template list and preview · 2026-12-03 to 2026-12-04 · SOK KIMHENG
- [ ] PT-013: Host: Search templates · 2026-12-07 to 2026-12-09 · SOK KIMHENG
- [ ] PT-014: Guest: Invitation link and QR code · 2026-12-07 to 2026-12-09 · SAN MEYHIENG
- [ ] PT-015: Guest: Home page · 2026-12-03 to 2026-12-07 · SOENG PRAKBORMEY
- [ ] PT-016: Guest: Featured templates · 2026-12-08 to 2026-12-09 · SOENG PRAKBORMEY

## 4. Sprint 2 (week 3, 2026-12-10 to 2026-12-16)

- [ ] PT-017: Admin: Sign in · 2026-12-10 to 2026-12-11 · PHE RITHIKA
- [ ] PT-018: Admin: Hosts · 2026-12-14 to 2026-12-16 · PHE RITHIKA
- [ ] PT-019: Admin: Templates · 2026-12-10 to 2026-12-16 · SOK KIMHENG
- [ ] PT-020: Host: Profile and settings · 2026-12-10 to 2026-12-16 · SAN MEYHIENG
- [ ] PT-021: Host: Create invitation · 2026-12-10 to 2026-12-16 · SAR VICHADA
- [ ] PT-022: Guest: Invitation page · 2026-12-10 to 2026-12-16 · SOENG PRAKBORMEY

- [ ] **Milestone: Sprint 2 review: sign in and sample pages for all 3 roles** · 2026-12-16

## 5. Sprint 3 (week 4, 2026-12-17 to 2026-12-23)

- [ ] PT-023: Admin: Hosts management · 2026-12-17 to 2026-12-23 · SAR VICHADA
- [ ] PT-024: Admin: Khmer content · 2026-12-17 to 2026-12-18 · SOENG PRAKBORMEY
- [ ] PT-025: Admin: Categories management · 2026-12-17 to 2026-12-18 · SOK KIMHENG
- [ ] PT-026: Host: Template editor (canvas, text, colours) · 2026-12-17 to 2026-12-23 · PHE RITHIKA
- [ ] PT-027: Host: Save invitation (draft, publish, unpublish) · 2026-12-17 to 2026-12-23 · SAN MEYHIENG
- [ ] PT-028: Host: Upload photos and files · 2026-12-21 to 2026-12-23 · SOENG PRAKBORMEY
- [ ] PT-029: Host and Guest: Event location and directions · 2026-12-21 to 2026-12-23 · SOK KIMHENG

## 6. Sprint 4 (week 5, 2026-12-24 to 2026-12-31)

- [ ] PT-030: Admin: Templates management · 2026-12-24 to 2026-12-31 · SOK KIMHENG
- [ ] PT-031: Host: Editor save (draft copy, undo, redo, reset, finalize) · 2026-12-24 to 2026-12-31 · PHE RITHIKA
- [ ] PT-032: Host: Guests (add, import, groups, plus-ones) · 2026-12-24 to 2026-12-31 · SAN MEYHIENG
- [ ] PT-033: Host: Several events and programme · 2026-12-28 to 2026-12-31 · SAR VICHADA
- [ ] PT-034: Host: Wishlist (save favorite templates) · 2026-12-24 to 2026-12-25 · SOENG PRAKBORMEY
- [ ] PT-035: Host: Wording in English and Khmer · 2026-12-28 to 2026-12-31 · SOENG PRAKBORMEY
- [ ] PT-036: Guest: Open invitation by link or QR (real data) · 2026-12-24 to 2026-12-25 · SAR VICHADA

- [ ] **Milestone: Sprint 4 review: invitations can be made, saved and opened by guests** · 2026-12-31

## 7. Sprint 5 (weeks 6–7, 2027-01-04 to 2027-01-11)

- [ ] PT-037: Admin: Invitations · 2027-01-04 to 2027-01-06 · SAR VICHADA
- [ ] PT-038: Host: Cart and payment · 2027-01-04 to 2027-01-11 · PHE RITHIKA
- [ ] PT-039: Host: My invitations (edit, duplicate, delete, restore) · 2027-01-08 to 2027-01-11 · SAR VICHADA
- [ ] PT-040: Host: Reminders and alert emails (RSVP replies, event tomorrow, thank-you, history) · 2027-01-04 to 2027-01-11 · SOENG PRAKBORMEY
- [ ] PT-041: Host: Personal link and QR for each guest · 2027-01-04 to 2027-01-06 · SOK KIMHENG
- [ ] PT-042: Host: Gift QR · 2027-01-08 to 2027-01-11 · SOK KIMHENG
- [ ] PT-043: Guest and Host: RSVP (reply, totals, who opened, meals) · 2027-01-04 to 2027-01-11 · SAN MEYHIENG

- [ ] **Milestone: Sprint 5 review: guests, RSVP, payment and alert emails work** · 2027-01-11

## 8. Sprint 6 (week 8, 2027-01-12 to 2027-01-18)

- [ ] PT-044: Admin: Orders and payments · 2027-01-12 to 2027-01-18 · PHE RITHIKA
- [ ] PT-045: Admin: Overview · 2027-01-12 to 2027-01-13 · SAR VICHADA
- [ ] PT-046: Admin: Event types and template styles · 2027-01-15 to 2027-01-18 · SOENG PRAKBORMEY
- [ ] PT-047: Admin: Plans (free, subscription, one-time) · 2027-01-12 to 2027-01-13 · SOK KIMHENG
- [ ] PT-048: Host: Dashboard (real data) · 2027-01-12 to 2027-01-18 · SAN MEYHIENG
- [ ] PT-049: Host: Download and print the invitation (PDF or image) · 2027-01-14 to 2027-01-18 · SAR VICHADA
- [ ] PT-050: Host: Plans (choose a plan, pay once or subscribe) · 2027-01-14 to 2027-01-18 · SOK KIMHENG
- [ ] PT-051: Guest and Host: Wishes · 2027-01-12 to 2027-01-14 · SOENG PRAKBORMEY

- [ ] **Milestone: Sprint 6 review: real data, plans, download and print** · 2027-01-18

## 9. Sprint 7 (week 9, 2027-01-19 to 2027-01-22)

- [ ] PT-052: Admin: New templates (graduation, Khmer New Year, memorial, anniversary) · 2027-01-19 to 2027-01-22 · PHE RITHIKA
- [ ] PT-053: Admin: New templates (birthday, house blessing, baby celebration, corporate event) · 2027-01-19 to 2027-01-22 · SAN MEYHIENG
- [ ] PT-054: Admin: New templates (modern minimalist) · 2027-01-19 to 2027-01-22 · SAR VICHADA
- [ ] PT-055: Admin: New templates (wedding, engagement, monk ordination, merit-making, general) · 2027-01-19 to 2027-01-22 · SOENG PRAKBORMEY
- [ ] PT-056: Host: Filter templates by event, style and language · 2027-01-19 to 2027-01-22 · SOK KIMHENG

- [ ] **Milestone: Feature freeze (no new features)** · 2027-01-19

- [ ] **Milestone: Final delivery** · 2027-01-22

## Risks

| Risk | Chance | Impact | What we do |
|---|---|---|---|
| An early task is late and blocks the tasks after it | Medium | High | We do the early tasks first (project setup, sign in, saving invitations, guests). If one is more than 2 days late, we move the tasks after it and help each other. Owner: PHE RITHIKA. |
| The template editor is too big | High | High | We split it in two: canvas with text and colours in Sprint 3, saving in Sprint 4. Fonts, music and photo editing are not included. Owner: PHE RITHIKA. |
| Paying by QR is harder than we think | Medium | High | We start the cart in Sprint 5. If it does not work, we show the QR and the admin marks the order as paid. Owner: PHE RITHIKA. |
| Plans and payment are too much for Sprint 6 | Medium | High | We build the free plan and the one-time payment first, and the subscription last. Owner: SOK KIMHENG. |
| Download and print looks different from the screen | Medium | Medium | We test PDF and image export early in Sprint 6 with Khmer text. Owner: SOK KIMHENG. |
| Khmer text or dates look wrong | Medium | Medium | We test Khmer text early (Sprint 3) on phone and desktop. Owner: SOENG PRAKBORMEY. |
| A member cannot work for some time | Medium | High | We keep code and documents shared, and give the important tasks to other members. Owner: PHE RITHIKA. |
| The course calendar or holidays are different from our plan | High | Medium | We assumed holidays on 29 Dec, 1 Jan and 7 Jan. After importing, we check the dates on GIC ITC. Owner: PHE RITHIKA. |
| We try to build too much | Medium | High | Features outside the plan stay out. We add them only if there is time left after the feature freeze. Owner: all members. |

## Changes to the plan

| Date | Change | Why |
|---|---|---|
| 2026-11-26 | The plan starts on 26 Nov and ends on 22 Jan, with one-week sprints | To match the course calendar. |
| 2026-11-26 | We use Next.js with MongoDB | The team decided to use only Next.js. |
| 2026-11-26 | Database design is split into Admin and Host and Guest | Each part has its own owners. |
| 2026-11-26 | Tasks are ordered by what they need first, and sign in is in Sprint 1 | So nobody waits for another member. |
| 2026-11-26 | Plans (free, subscription, one-time) and alert emails added; sharing by Telegram removed; "Download and print the invitation" added | They are high priority in our feature list or in the project description. Some 5-day tasks were shortened to make room. |

### Scrum estimates and dependencies (reference for website task fields)

The table gives the proposed **Points** and **Notes**. The importer may ignore it; enter or check these values in the task details after importing.

| Task | Sprint | SP | Priority | Est. hours | Depends on | Acceptance / Done when |
|---|---|---:|---|---:|---|---|
| PT-001 | S0 | 1 | P0 | 8 | none | All five members met and agreed on the goal, the roles and the way we work. |
| PT-002 | S0 | 5 | P0 | 24 | PT-001 | The main site, the admin site and the shared database code run on one computer and are in the repository. |
| PT-003 | S0 | 1 | P1 | 8 | PT-001 | The repository exists, all members can push, and the README and plan.md are in it. |
| PT-004 | S0 | 1 | P0 | 8 | PT-001 | Requirements and user stories for Host, Guest and Admin are written and the team agrees. |
| PT-005 | S0 | 3 | P1 | 16 | PT-004 | Collections and fields for the admin site are drawn and checked by the team. |
| PT-006 | S0 | 3 | P1 | 16 | PT-004 | Collections and fields for the main site are drawn and checked by the team. |
| PT-007 | S0 | 1 | P0 | 8 | PT-004 | Figma prototype of the main pages is ready and the team agrees. |
| PT-008 | S1 | 3 | P0 | 16 | PT-002, PT-005 | Admin can see the categories list (sample data) on the admin site. |
| PT-009 | S1 | 8 | P0 | 40 | PT-002, PT-006 | A person can sign up, sign in, reset the password and sign out. Pages are protected by role. |
| PT-010 | S1 | 3 | P1 | 16 | PT-002, PT-007 | Host dashboard and the list of invitations show with sample data. |
| PT-011 | S1 | 5 | P1 | 24 | PT-002, PT-007 | Host can preview an invitation on phone and desktop size. |
| PT-012 | S1 | 3 | P0 | 16 | PT-002, PT-007 | Host can see the template list and open a preview. |
| PT-013 | S1 | 5 | P1 | 24 | PT-002, PT-007 | Host can search templates by name. |
| PT-014 | S1 | 5 | P1 | 24 | PT-002, PT-007 | A link and a QR code open a sample invitation page. |
| PT-015 | S1 | 5 | P1 | 24 | PT-002, PT-007 | The home page shows with sample data. |
| PT-016 | S1 | 3 | P1 | 16 | PT-002, PT-007 | Featured templates show on the home page with sample data. |
| PT-017 | S2 | 3 | P1 | 16 | PT-009 | Admin can sign in and out on the admin site. Other roles cannot enter. |
| PT-018 | S2 | 5 | P0 | 24 | PT-017 | Admin can see the list of hosts on the admin site. |
| PT-019 | S2 | 8 | P1 | 40 | PT-008 | Admin can see the templates list and open one. |
| PT-020 | S2 | 8 | P1 | 40 | PT-009 | Host can see and change their profile and settings. |
| PT-021 | S2 | 8 | P0 | 40 | PT-009, PT-012 | Host can pick a template and fill in the event details in a form. |
| PT-022 | S2 | 8 | P0 | 40 | PT-014 | The invitation page shows the event, text and photo from the database. |
| PT-023 | S3 | 8 | P1 | 40 | PT-018 | Admin can search, block and unblock a host. |
| PT-024 | S3 | 3 | P1 | 16 | PT-008 | Admin can manage Khmer names and text. |
| PT-025 | S3 | 3 | P1 | 16 | PT-008 | Admin can add, edit and delete categories in the database. |
| PT-026 | S3 | 8 | P0 | 40 | PT-021 | Host can change text, colours and the canvas of a template. |
| PT-027 | S3 | 8 | P0 | 40 | PT-021 | Host can save a draft, publish it and unpublish it. |
| PT-028 | S3 | 5 | P1 | 24 | PT-021 | Host can upload photos and files and they show on the invitation. |
| PT-029 | S3 | 5 | P1 | 24 | PT-021, PT-022 | Host picks a place on the map and the guest sees it with directions. |
| PT-030 | S4 | 8 | P0 | 40 | PT-019, PT-026 | Admin can add, edit, hide and delete templates. |
| PT-031 | S4 | 8 | P1 | 40 | PT-026 | Host can save a draft copy, undo, redo, reset and finalize a design. |
| PT-032 | S4 | 8 | P0 | 40 | PT-027 | Host can add and import guests, make groups and set plus-ones. |
| PT-033 | S4 | 5 | P1 | 24 | PT-027 | One invitation can have several events with a programme. |
| PT-034 | S4 | 3 | P1 | 16 | PT-012 | Host can save and remove favorite templates. |
| PT-035 | S4 | 5 | P1 | 24 | PT-021, PT-024 | Host can write the invitation in English and Khmer. |
| PT-036 | S4 | 3 | P0 | 16 | PT-027, PT-022 | A published invitation opens by link or QR with the real data. |
| PT-037 | S5 | 5 | P1 | 24 | PT-027 | Admin can see, search and take down invitations. |
| PT-038 | S5 | 8 | P0 | 40 | PT-027 | Host can add an invitation to the cart and pay. The order is saved. |
| PT-039 | S5 | 3 | P1 | 16 | PT-027 | Host can edit, duplicate, delete and restore an invitation. |
| PT-040 | S5 | 8 | P1 | 40 | PT-032, PT-036 | Host can schedule reminders and thank-you messages. Emails go in Khmer or English and are queued and retried. Host gets an email when a guest replies. Guests get the event reminder and a change notice. Host can see the history. |
| PT-041 | S5 | 5 | P1 | 24 | PT-032, PT-036 | Each guest has a personal link and QR code. |
| PT-042 | S5 | 3 | P1 | 16 | PT-027 | Host can add a gift QR code and guests see it. |
| PT-043 | S5 | 8 | P1 | 40 | PT-032, PT-036 | Guests can reply and the host sees totals, who opened and meal choices. |
| PT-044 | S6 | 8 | P1 | 40 | PT-038 | Admin can see orders and payments and mark an order as paid. |
| PT-045 | S6 | 3 | P1 | 16 | PT-044, PT-037, PT-018 | The admin overview shows real numbers. |
| PT-046 | S6 | 3 | P1 | 16 | PT-025 | Admin can manage event types and template styles. |
| PT-047 | S6 | 3 | P1 | 16 | PT-038 | Admin can create and edit the free plan, the subscription and the one-time payment, with their prices, duration and limits, without changing code. |
| PT-048 | S6 | 8 | P1 | 40 | PT-043, PT-038 | The host dashboard shows real numbers from the database. |
| PT-049 | S6 | 5 | P1 | 24 | PT-027, PT-026 | Host can download the invitation as a PDF or image for printing. |
| PT-050 | S6 | 5 | P1 | 24 | PT-038, PT-047 | A pricing page compares the plans. New accounts start on Free. Host can subscribe or pay once for one invitation, locked features show an upgrade prompt, and the host sees the plan and days left. |
| PT-051 | S6 | 5 | P1 | 24 | PT-036 | Guests can send a wish and the host can read it. |
| PT-052 | S7 | 5 | P1 | 32 | PT-030 | Graduation, Khmer New Year, memorial and anniversary templates are in the database, in Khmer, English and bilingual versions. |
| PT-053 | S7 | 5 | P1 | 32 | PT-030 | Birthday, house blessing, baby celebration and corporate event templates are in the database, in Khmer, English and bilingual versions. |
| PT-054 | S7 | 5 | P1 | 32 | PT-030 | Minimalist templates for wedding, engagement, birthday and graduation are in the database and have the Minimalist tag. |
| PT-055 | S7 | 5 | P1 | 32 | PT-030 | Wedding, engagement, monk ordination, merit-making and general templates are in the database, in Khmer, English and bilingual versions. |
| PT-056 | S7 | 5 | P1 | 32 | PT-046 | Host can filter templates by event, style (including Minimalist) and language, and the result count updates. |

### Sprint 0 task descriptions (reference for website Notes)

Sprint 0 is the Start and Design phases (PT-001 to PT-007). Use these when entering Notes on the course website.

| Task | Description |
|---|---|
| PT-001 | Agree on goal, roles, and the weekly review routine. |
| PT-002 | Create the Next.js main site, the admin site and the shared MongoDB code so everyone can run them. |
| PT-003 | Create the shared repository with README and plan.md, and give all members access. |
| PT-004 | Write requirements and user stories for Host, Guest and Admin. |
| PT-005 | Draw the collections and fields for the admin site. |
| PT-006 | Draw the collections and fields for the main site (Host and Guest). |
| PT-007 | Make the Figma prototype of the main pages and templates. |

### Sprint goals and capacity (planning reference)

| Period | Sprint goal | Task count | Story Points |
|---|---|---:|---:|
| Sprint 0 (26 Nov–2 Dec) | Requirements, project setup, repository, database design, prototype | 7 | 15 |
| Sprint 1 (12-03 to 12-09) | Sign in and first pages with sample data | 9 | 40 |
| Sprint 2 (12-10 to 12-16) | Admin sign in, host profile, create invitation, invitation page | 6 | 40 |
| Sprint 3 (12-17 to 12-23) | Template editor, saving invitations, uploads, map | 7 | 40 |
| Sprint 4 (12-24 to 12-31) | Guests, saving the editor, templates management, wishlist | 7 | 40 |
| Sprint 5 (01-04 to 01-11) | Cart and payment, RSVP, reminders and alert emails, QR codes | 7 | 40 |
| Sprint 6 (01-12 to 01-18) | Orders, real data, wishes, plans, download and print | 8 | 40 |
| Sprint 7 (01-19 to 01-22) | New templates, filters and wrap-up | 5 | 25 |
| **Total** | | **56** | **280** |

Each member has about 39 working days (5 days in each of the seven sprints, 4 in Sprint 7, and a few in Sprint 0). The team must confirm these numbers and check them against the website calendar.

**Definition of Done:** see the README (When is a task done?).

Before saving the baseline, check task owners, dates, holidays (we assumed 29 Dec, 1 Jan and 7 Jan), Story Points, dependencies and each member's weekly load on GIC ITC.
