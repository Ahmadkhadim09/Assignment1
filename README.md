# Campus Bites

A fictional campus cafeteria information website built with plain HTML and one shared CSS file.

## View the site

Open `src/index.html` in a browser. Navigate to Menu, Deals, How to Order and Feedback. No build or backend is required. The feedback form is a static assignment demonstration; it does not send feedback.

## Team

| Page | GitHub member | Feature branch |
| --- | --- | --- |
| Home | Ahmadkhadim09 | feature/home-page |
| Menu | aimnzee | feature/menu-page |
| Deals | MuhammadAwais-28 | feature/deals-page |
| How to Order | Ahsinys | feature/order-page |
| Feedback & Contact | kimsangheui | feature/feedback-page |

## Review and release

- Feature PRs target develop and require two genuine approvals.
- release/v1.0 is the release candidate. Its draft production PR must wait for Home to merge into develop and for team QA.
- Production PR: release/v1.0 → main, requiring three genuine approvals.
- After production merge, synchronize release/v1.0 → develop through a PR if there are release-only changes.
- Never bypass rules or reuse approvals from reversed PR #9 as approval of the new Home page.

## Integration notes

Menu PR #8 retains Aimen's original commit. A merge commit resolves the shared CSS conflict and retains existing Deals, Order and Feedback contributions. This preserves original commit identities; it is not a demonstration of the rubric's member-performed rebase.

Reversed PR #9 remains closed as historical evidence. Its head was develop and base was feature/home-page; the Home file was empty. A correctly directed replacement implements Home.

## QA checklist for all members

- Open all five pages at desktop, tablet and phone widths (including 320px).
- Follow every navigation link and check keyboard focus.
- Check Menu has four categories with three priced items each.
- Check the daily special and three combo deals.
- Check the four ordering steps, peak-hour guidance and pickup rules.
- Check Home location/hours match Feedback.
- Check Feedback name, email and message fields; submission is static.
- Capture authentic screenshots for submission: rules, issues, PR approvals, conflict resolution and final merges.
