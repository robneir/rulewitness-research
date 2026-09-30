# RuleWitness research

A public research intake for teams checking whether changes to pricing, billing, commission or operational rules preserve the behavior they intend.

The [working prototype](https://rulewitness-prototype-20260930.vercel.app) compares a limited exact-arithmetic formula language. It does not execute production code or approve migrations. We have not established a distinctive commercial advantage or validated customer demand.

## Help identify an unmet need

[Describe a real workflow](https://github.com/robneir/rulewitness-research/issues/new?template=workflow.yml) if you own or implement rule changes and existing tests or tools leave a concrete problem. A short description is enough; a sanitized example is optional. Reports that existing tools already solve the problem are equally useful.

GitHub issues and submitted account identities are public. Do not include customer data, proprietary formulas, credentials, personal information or unpatched security vulnerabilities. No email address, private repository access, payment or call is requested. Submissions are research input, not a service commitment.

## Evidence so far

- A stronger literal/boundary sampler found all nine synthetic differences in our authored corpus. Sampling cannot prove equivalence, but this removes the original benchmark’s apparent detection advantage.
- Eight known public defect records exposed important gaps involving native arithmetic, state, units and intended policy. None was a new discovery by this project.
- A manually reduced Vendure threshold case was also detected by simple boundary enumeration.

[Read the full field review](https://rulewitness-prototype-20260930.vercel.app/field-review.html), [synthetic results](https://rulewitness-prototype-20260930.vercel.app/benchmark-report.html), and [venture thesis](https://rulewitness-prototype-20260930.vercel.app/venture-thesis.html). Existing verification tools are alternatives to evaluate, not capabilities this project claims to have invented.

## What would justify further work

A repeated, specific problem that existing approaches do not adequately solve; checks tied to actual source versions and faithful runtime behavior; and evidence that teams would adopt the result without bespoke implementation for every rule. Interest, stars and issue counts alone will not be treated as willingness to pay.

This repository contains the research intake and findings links. It is not the production verifier source repository.
