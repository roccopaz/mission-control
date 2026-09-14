# Mission Control

An operations dashboard for reviewing projects, agent activity, and business information in one place.

[Screenshot walkthrough](https://roccopaz.github.io/mission-control/preview.html) · [Portfolio](https://roccopaz.github.io/)

## The problem

Running a business alongside several automation workflows creates separate places to check project status, tasks, and performance. I built Mission Control as a central interface for reviewing that information and deciding what needs attention.

## My role and approach

I defined the operational purpose and refined the dashboard through AI-assisted development. I organized the interface around projects, agent activity, revenue, content, and research so related information could be reviewed together.

The implementation uses HTML, CSS, and JavaScript in a self-contained page. CSS Grid and Flexbox support the layout, while the public version uses browser storage for local state. This keeps the demonstration easy to run without a private backend.

## Public demo and private integrations

**The public dashboard uses sample data. Its figures are not verified business results.** Changes in the demo are stored in the visitor's browser; the public source is not a deployment of my private business integrations.

The private workflow has been described with these integrations. Their live connection status cannot be established from the public repository:

| Integration | Business purpose |
| --- | --- |
| Amazon SP-API | Sales, orders, and fulfillment information |
| YNAB | Spending and budget information |
| Brave Search | Research and trend discovery |
| Postiz | Scheduled and published content |

The ISS tracker and quote API are supplementary display features, separate from the business integrations. They should not be counted as evidence of business functionality or operational impact.

## Result and limits

The dashboard provides a single interface for reviewing operational information. The public demo demonstrates the interface and local interactions. It does not establish time savings, financial returns, or production reliability for private services.

## Public source status

The current public `index.html` ends mid-script inside `renderClientTable`. A local browser check showed an empty dashboard beneath the navigation. The interactive demo needs repair before it can be used as a working demonstration. The linked screenshot walkthrough remains available.

## Run and check the demo

Open `index.html` in a browser, or serve this folder with a local static web server. No build step is required.

When validating changes, check navigation between views, local state after a reload, narrow-screen layout, and browser console errors. Testing the public interface does not validate credentials, data freshness, or private API connections.

## Technology and AI assistance

- HTML, CSS, and JavaScript for the interface and local interactions.
- Claude Code and OpenClaw for AI-assisted scaffolding, debugging, and iterative refinement.
- Claude Sonnet, Claude Opus, and OpenAI Codex were used in the development workflow.

AI tools contributed to the implementation. My contribution was defining the purpose, directing the workflow, and refining the dashboard; this project should be evaluated with that disclosure in mind.

## Files

- `index.html`: interactive public dashboard with sample data.
- `preview.html`: screenshot walkthrough.
- `images/`: existing dashboard screenshots, which may show a different version from the public demo.

Rocco Paz · Texas State University CIS student · Expected graduation December 2027
