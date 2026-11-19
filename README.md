# GitHub Copilot 101

An interactive GitHub employee orientation presented by **Lessley Dennington | Senior Solutions Engineer**.
The 15-slide deck retains the terminal-green theme and reserves time for a live demo and Q&A within a 45-minute session.

## View the presentation

Open `index.html` in a browser, or serve this directory with `python3 -m http.server 8000`
and visit <http://localhost:8000>. No build or package installation is required.
If publishing with GitHub Pages, serve the repository root; the presentation is self-contained in `index.html`.

Use the arrow keys, space bar, navigation dots, scrolling, or touch gestures to move through the slides. The final slide includes PDF and PowerPoint export controls.
PDF uses the browser's print dialog; enable background graphics to retain the theme.
PowerPoint export creates an editable text summary, not a pixel-perfect copy of the interactive slides.
Google Fonts and the PptxGenJS export library load from external CDNs; check connectivity before presenting.

## Session pacing

| Elapsed time | Slides | Focus |
| --- | --- | --- |
| 00–03 | 1–3 | Welcome, agenda, and poll |
| 03–10 | 4–11 | Copilot, surfaces, suggestions, CLI, App customizations and automations, cloud agent, and review |
| 10–18 | 12–13 | Fusion and data handling |
| 18–35 | 14 | Live demo |
| 35–43 | 15 | Q&A |
| 43–45 | 15 | Resources and one workflow to try this week |

Keep the concept slides brief. Stop the demo at minute 35 to protect Q&A.

## Demo preparation

- Use a separate, non-sensitive sample repository with a reproducible small bug, a runnable test suite, and a known-good fix. This presentation repository is not the demo application.
- Confirm employee access, the chosen editor/client, model availability, and applicable internal data-handling rules. Public product documentation does not establish GitHub employee entitlements or internal policy.
- Rehearse the same task through explanation, a minimal fix plus regression test, and diff/test review. Confirm the regression test fails before the fix and passes afterward. Demonstrate tool approval deliberately; do not grant broad access just to keep the demo moving.
- Prepare a before/after diff and captured test output as a fallback. If authentication, network access, or generation stalls, use that evidence rather than consuming Q&A.
- Keep cloud-agent PR creation as a verbal comparison unless it is already prepared; the core demo does not depend on a cloud run completing live.

## Sources and maintenance

Adapted from the original [GitHub Copilot 101 gist](https://gist.github.com/AndreaGriffiths11/f9e625a573856fe5b2247e10beee89c3)
by Andrea Griffiths; retained here as source attribution, not presenter identity.

Content reviewed against official GitHub documentation on November 17, 2026:

- [GitHub Copilot Agents: responsible use, context, limitations, and permission controls](https://docs.github.com/en/enterprise-cloud@latest/copilot/responsible-use/agents)
- [Copilot on GitHub.com and GitHub Mobile](https://docs.github.com/en/enterprise-cloud@latest/copilot/concepts/copilot-surfaces/copilot-on-github)
- [Starting GitHub Copilot cloud agent sessions](https://docs.github.com/en/enterprise-cloud@latest/copilot/how-tos/use-copilot-agents/cloud-agent/start-copilot-sessions)
- [Using GitHub Copilot CLI](https://docs.github.com/en/copilot/how-tos/copilot-cli/use-copilot-cli)
- [About GitHub Copilot agents: CLI and Copilot App](https://docs.github.com/en/enterprise-cloud@latest/copilot/concepts/agent-capabilities/about-agents/about-github-copilot-agents)
- [About GitHub Copilot Fusion](https://docs.github.com/en/enterprise-cloud@latest/copilot/concepts/models/copilot-fusion)
- [Customizing the GitHub Copilot app](https://docs.github.com/en/enterprise-cloud@latest/copilot/how-tos/github-copilot-app/customize-github-copilot-app)
- [Using automations in the GitHub Copilot app](https://docs.github.com/en/enterprise-cloud@latest/copilot/how-tos/github-copilot-app/using-automations)
- [Choosing a Copilot code review effort level](https://docs.github.com/en/enterprise-cloud@latest/copilot/how-tos/use-copilot-agents/use-code-review#choosing-a-review-effort-level)
- [Content exclusion and its limitations](https://docs.github.com/en/enterprise-cloud@latest/copilot/concepts/security-governance-and-network-settings/content-exclusion)
- [Supported AI models](https://docs.github.com/en/enterprise-cloud@latest/copilot/reference/ai-models/supported-models)
- [Repository custom instructions](https://docs.github.com/en/enterprise-cloud@latest/copilot/how-tos/copilot-on-github/customize-copilot/add-custom-instructions/add-repository-instructions)
- [Custom agents, skills, and MCP in Copilot CLI](https://docs.github.com/en/enterprise-cloud@latest/copilot/how-tos/copilot-cli/use-copilot-cli/invoke-custom-agents)

The deck intentionally omits usage statistics, a fixed model roster, dated release badges, and blanket
training/retention guarantees. Recheck live documentation, current terms, and the actual demo setup before reuse.
