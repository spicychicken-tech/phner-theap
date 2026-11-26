# Phner Theap

**A web platform for designing and sharing digital invitations, built with Next.js and MongoDB.**

**Course:** IT Project Management (I5, 2026–2027 Semester 1)  
**Team:** Spicy Chicken  
**Repository:** [spicychicken-tech/phner-theap](https://github.com/spicychicken-tech/phner-theap)  
**Project start:** 26 November 2026  
**Final delivery:** 22 January 2027  
**Plan file:** [plan.md](plan.md), version 1.0

> **Note, 26 November 2026:** Today is the first day. This README only describes what we plan to do. It does not say that any task is finished. To see real progress, look at the GitHub Issues, pull requests and tests.

## About the project

Phner Theap helps people create personal invitations for weddings, engagements, birthdays, graduations and traditional celebrations. A **Host** chooses a template, edits it, adds the event details and the guest list, then sends the invitation by link or QR code. A **Guest** opens it on a phone or computer without making an account. The guest can see the event place on a map, reply, and send a wish. The Host can also pay online, collect money gifts by QR code, and download the invitation to print as a card.

An **Admin** controls the platform from a separate site with its own subdomain. Host and Guest share one main site, and the pages change by role. Both sites read and write one MongoDB database. The platform supports Khmer and English.

### Main features

The full list of must-have features, and what we leave out, is in [MVP_SCOPE.md](docs/MVP_SCOPE.md).

## Tools

| Part | Tool |
| --- | --- |
| Framework | Next.js, frontend and backend together |
| Database | MongoDB with Mongoose, one database for both sites |
| Design | Figma |
| Code and tasks | GitHub |

## Where to see our work

| Place | What it shows | How to use it |
| --- | --- | --- |
| [plan.md](plan.md) | Team, schedule, milestones, 56 tasks with owners and dates, risks, estimates, dependencies and done conditions | Read first to know what we promised |
| [docs/MVP_SCOPE.md](docs/MVP_SCOPE.md) | What is in and out of the project | Check a feature against it |
| [docs/PROJECT_CHARTER.md](docs/PROJECT_CHARTER.md) | Purpose, goal, roles and how we work together | Read for the big picture |
| [GitHub Issues](https://github.com/spicychicken-tech/phner-theap/issues) | Tasks in progress and what blocks them | Search the task ID, like `PT-009` |
| [Pull requests](https://github.com/spicychicken-tech/phner-theap/pulls) | Changes, comments and reviews | Each one names its task ID |
| [Commits](https://github.com/spicychicken-tech/phner-theap/commits) | Every change to code and documents | Read together with the pull request and tests |
| GIC ITC website | The plan the course uses to check us | Keep it the same as plan.md |

**Please note:** plan.md and the website must stay the same. The one-line task format in plan.md is there for the importer, so we do not change it only to look nicer on GitHub. Story Points, priority and "done when" in plan.md may need to be typed into the website by hand.

## How we track progress

Every task has an ID from **`PT-001` to `PT-056`**. The same ID goes in the plan, the issue title, the branch name, the pull request and the commit message.

An issue moves through five steps:

1. **Backlog:** planned, not ready yet.
2. **To do:** ready, with an owner.
3. **In progress:** someone is working on it.
4. **In review:** finished by the owner, waiting for a teammate to check.
5. **Done:** it meets its done condition, a teammate checked it, and there is proof.

Each issue should show the task ID, owner, sprint, priority, date, Story Points, dependencies, done condition and a link to proof. A closed issue or a ticked box is only what we say. Proof is what counts.

### Example

- **Plan:** `PT-009`, Host and Guest: Authentication.
- **Issue:** `PT-009: Host and Guest authentication`.
- **Branch:** `feature/PT-009-authentication`.
- **Commit:** `feat(PT-009): add sign in and sign up`.
- **Pull request:** names `PT-009`, links the issue, says how it was tested.
- **Proof:** a recording or test result of sign up, sign in, password reset and sign out.

This is only an example of the workflow. It does not mean `PT-009` is done.

### When is a task done?

- It does what its done condition in [plan.md](plan.md) says.
- The work is in the repository and easy to find.
- A teammate reviewed or tested it.
- There is proof, such as a link, a recording or a test result.

A milestone needs something we can show. A list of ticked boxes is not enough.

## How to run

This is a **Next.js web app that uses MongoDB**.

1. Install the current LTS version of [Node.js](https://nodejs.org/).
2. Prepare a MongoDB database, local or online.
3. Clone the repository:

   ```bash
   git clone https://github.com/spicychicken-tech/phner-theap.git
   cd phner-theap
   ```

4. When task `PT-002` creates the project, we will add the install steps, the environment file and the commands to start the main site and the admin site.

Before `PT-002` is done, there is nothing to run yet.

## Working with Git

Make one branch for each task:

```text
feature/PT-032-host-guests
fix/PT-043-rsvp-count
docs/PT-004-requirements
```

Write commits like this:

```text
feat(PT-032): add guest import
fix(PT-043): correct RSVP totals
docs(PT-004): write user stories
```

Open a pull request that has the task ID, what changed, how you tested it, and proof. Ask a teammate to review it before merging.

We do not judge people by number of commits or lines of code. We look at code, reviews, testing, design and documents, with proof.

## Weekly check

Every week the team checks progress and makes sure the issues, this repository and the course website say the same thing. We answer these questions: which tasks are done and what is the proof, what is blocked or late, what did we show or test, did the scope, dates, owners or risks change, and what is next.

If we write weekly reports, they go in `docs/progress/` (for example `week-01.md`). That folder does not exist yet.

## For the teacher and the AI reviewer

To check our progress:

1. Read this README and [plan.md](plan.md) to see what we planned.
2. Find the issues, pull requests and commits with task IDs `PT-001` to `PT-056`.
3. For each task, decide: planned, in progress, reported done, verified done, blocked or unknown. It is **verified done** only if the proof matches the done condition.
4. Compare with the dates and milestones, and with the GIC ITC website if you can open it.
5. Look at each member's real contribution (code, reviews, tests, documents), not only commit counts.
6. If something has no record, please write "unknown". Please do not guess.

Progress formula:

```text
Progress (%) = Story Points of verified-done tasks ÷ 280 × 100
```

This shows how much of the plan is done. It does not show software quality or hours worked. In your summary, please include: what you looked at, progress out of 56 tasks and 280 points, the current sprint, milestones, work by each member, risks, and next tasks with owners. If only the README and plan are available, the work is planned and not verified.

## Risks

The risks, their owners and our answers are in [plan.md](plan.md). To stay on time, we add no new features after the freeze on 19 January 2027.

## Licenses and assets

Before using a template, a font (including Khmer fonts) or an image, we write down where it came from and its license. This README does not give a license to the repository.

---

**Where the detailed requirements are:** [Project plan, v1.0](plan.md). When the scope, dates, setup or rules change, we update this README and keep the plan and the course website the same.
