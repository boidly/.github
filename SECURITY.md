# Security policy

This policy covers every repository in the Boidly organization that has no security policy of its own.

## Reporting a vulnerability

Report privately, never in a public issue or pull request:

- Email security@boidly.com, or
- Use GitHub's private vulnerability reporting on the affected repository where it is enabled.

Please include what you found, how to reproduce it, and what an attacker could do with it. A proof of concept helps most. Boidly's own review rule is that a finding blocks a merge when it comes with a witness that anyone can rerun, so we value reports that carry one.

We acknowledge every report, keep you informed while we fix it, agree on a disclosure date with you, and credit you unless you ask us not to.

## Scope

In scope: the Boidly kernel, its hook adapters and drivers, the Open Coordination Protocol spec, the install script, and FlockBench at bench.boidly.dev.

Out of scope: vulnerabilities in the agent harnesses themselves, such as Claude Code, Codex or Cursor. Please report those to their vendors.
