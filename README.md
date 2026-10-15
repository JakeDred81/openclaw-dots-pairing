# OpenClaw Dots Pairing

A checked handoff procedure for an OpenClaw assistant and the user's existing OpenAI dot, using verified app/browser access or an optional established bounded file route.

## What it does

- Defines one execution owner and a bounded task brief.
- Verifies the account and exact dot conversation before dispatch.
- Sends once, reconciles uncertain outcomes, and checks the returned result.
- Preserves user approvals, privacy boundaries, dashboard focus, and resource limits.
- Separates substantive peer review from acknowledgment and from the user's final approval.
- Documents bounded file-envelope, receiver, acknowledgment and duplicate checks without installing transport code.

## Requirements

An existing dot available to the user's account and an authorized supported API or verified app/browser control route. Browser work uses OpenClaw's browser-automation skill. Apply the user's desktop-first and lifecycle preferences where present. The optional file branch requires separately established access, provenance checks and a working bounded receiver; this package supplies instructions and templates, not executable bridge or receiver code.

## Install

Install from the public repository's main branch using OpenClaw's supported Git route:

```sh
openclaw skills install git:JakeDred81/openclaw-dots-pairing@main
```

Review the files before installing. Git installs are not ClawHub-tracked, so `openclaw skills update` does not update this installation. Follow your installed OpenClaw version's Git/local-skill documentation for later updates.

## Use

Ask your OpenClaw assistant to use OpenClaw Dots Pairing for a specific task with your existing dot. Provide the dot identity if it is not already in scoped project context. Read [SKILL.md](SKILL.md) for the procedure and [the brief template](references/handoff-template.md) for the handoff contract.

## Boundaries and evidence

The original workflow was exercised in two browser-mediated exchanges: bounded research with a returned result, and onboarding with acknowledgment. Later operational work included desktop-app review handoffs and a bounded file-mailbox round trip with acknowledgment and duplicate handling. A receiver wake was observed, but delivery could be delayed and a new exchange needs a fresh bounded receiver or active read.

These observations are workflow evidence, not an end-to-end test of every route in this exact updated package. Its instructions guide checks but do not themselves enforce permissions, resource limits, authentication or exactly-once delivery. This is not a native dots API, unattended bridge, scheduler, or proof of usage savings. Work/Codex delegation remains subject to normal usage limits and billing rules. See [capability notes](references/capabilities.md), [route checks](references/routes.md) and [optional mailbox checks](references/peer-mailbox.md).

## Modification note

October 14, 2026: expanded the checked-handoff procedure to cover verified desktop-app routes, substantive review and correspondence continuity, complete-payload checks, evidence provenance, and optional bounded file exchanges. No executable transport was added. The original attribution and CC BY 4.0 terms are retained. AI-assisted documentation update through Jarvis/OpenClaw; substantive collaboration reviewed with Friday.

## Credit

Workflow requirements and proposal: **Jacob Frisby**. AI-assisted implementation and documentation: Jarvis through OpenClaw. Jacob reports conception on September 28, 2026; demonstrations followed October 3. No claim of first invention or official endorsement. See [ATTRIBUTION.md](ATTRIBUTION.md).

## License

Jacob Frisby licenses any copyright or similar rights he holds in these written instructions, documentation, and templates under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). No rights are claimed in underlying ideas, methods, or expression generated solely by AI without protectable human authorship.

When sharing under this license, provide the supplied attribution and notices, include the license text or link, retain the source link where reasonably practicable, indicate your modifications, and retain previous modification notices, as required by Section 3. These requirements may be met in any reasonable manner allowed by the license; applicable exceptions remain unaffected. Commercial reuse and adaptations are permitted.

See [LICENSE.txt](LICENSE.txt) for the unmodified legal terms.
