# OpenClaw Dots Pairing

A small, browser-mediated handoff procedure for an OpenClaw assistant and the user's existing OpenAI dot.

## What it does

- Defines one execution owner and a bounded task brief.
- Verifies the account and exact dot conversation before dispatch.
- Sends once, reconciles uncertain outcomes, and checks the returned result.
- Preserves user approvals, privacy boundaries, dashboard focus, and resource limits.

## Requirements

An existing dot available to the user's account, authorized signed-in browser access, OpenClaw browser control, and its browser-automation skill. This package supplies instructions and templates, not executable bridge code.

## Install

After this repository is publicly available, install from its main branch using OpenClaw's supported Git route:

```sh
openclaw skills install git:JakeDred81/openclaw-dots-pairing@main
```

Review the files before installing. Git installs are not ClawHub-tracked, so `openclaw skills update` does not update this installation. Follow your installed OpenClaw version's Git/local-skill documentation for later updates.

## Use

Ask your OpenClaw assistant to use OpenClaw Dots Pairing for a specific task with your existing dot. Provide the dot identity if it is not already in scoped project context. Read [SKILL.md](SKILL.md) for the procedure and [the brief template](references/handoff-template.md) for the handoff contract.

## Boundaries and evidence

The underlying workflow was exercised in two browser-mediated exchanges: bounded research with a returned result, and onboarding with acknowledgment. The skill bundle has passed static validation only; these observations do not establish end-to-end validation of the packaged skill. Its instructions guide checks but do not themselves enforce permissions, resource limits, or exactly-once delivery. This is not a native dots API, unattended bridge, scheduler, or proof of usage savings. Work/Codex delegation remains subject to normal usage limits and billing rules. See [capability notes](references/capabilities.md).

## Credit

Workflow requirements and proposal: **Jacob Frisby**. AI-assisted implementation and documentation: Jarvis through OpenClaw. Jacob reports conception on September 28, 2026; demonstrations followed October 3. No claim of first invention or official endorsement. See [ATTRIBUTION.md](ATTRIBUTION.md).

## License

Jacob Frisby licenses any copyright or similar rights he holds in these written instructions, documentation, and templates under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). No rights are claimed in underlying ideas, methods, or expression generated solely by AI without protectable human authorship.

When sharing under this license, provide the supplied attribution and notices, include the license text or link, retain the source link where reasonably practicable, indicate your modifications, and retain previous modification notices, as required by Section 3. These requirements may be met in any reasonable manner allowed by the license; applicable exceptions remain unaffected. Commercial reuse and adaptations are permitted.

See [LICENSE.txt](LICENSE.txt) for the unmodified legal terms.
