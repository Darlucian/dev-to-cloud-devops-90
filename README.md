# From Dev to DevOps: 90 Days

> A fullstack developer learning DevOps and AWS in public: daily notes, labs, projects, and a capstone.

**Day 1:** Mon, Nov 9, 2026 · **Day 90:** Sat, Feb 6, 2027
**Training:** DevOps Engineering, TS Academy (Aurora Cohort)
**Follow along:** X: [@wunderfashy] · LinkedIn: [https://www.linkedin.com/in/darlington-iroegbu-87b836293/] 

---

## Why this exists

I build apps, but I want to know how to ship, secure, and run them in production. For 90 days I'm learning DevOps and AWS in public and keeping everything in this repo as proof, including the things that break.

**Goals**
1. Gain real, provable skill (not just a certificate).
2. Get feedback from people who do this for a living.
3. Land a junior DevOps / cloud engineering role where I can keep growing.

## What I'm learning

- [ ] Linux command line: permissions, users, processes, services (`systemd`, `journalctl`), SSH keys
- [ ] Networking: IP/CIDR, DNS, ports, HTTP/TLS, firewalls
- [ ] Bash scripting
- [ ] Git and GitHub workflow (branches, pull requests, conflicts)
- [ ] Python basics for automation (alongside the course, from week 4)
- [ ] Docker and Docker Compose, image scanning with Trivy
- [ ] AWS: IAM, VPC, EC2, S3, RDS, load balancers, cost control
- [ ] Terraform: resources, state, modules, remote state, dev/prod environments
- [ ] CI/CD with GitHub Actions (including keyless AWS login with OIDC)
- [ ] Kubernetes basics (local cluster), Helm
- [ ] Monitoring and logging: Prometheus, Grafana, alerting
- [ ] Troubleshooting, runbooks, and post-incident write-ups

## Progress tracker

Planned from my class timetable; I adjust as I go.

| Week | Dates | Planned focus | Status |
|---|---|---|---|
| 1 | Nov 9 - 15 | Intro, setup, DevOps basics, Linux basics | 🟡 |
| 2 | Nov 16 - 22 | Linux command line | ⬜ |
| 3 | Nov 23 - 29 | Networking and Bash | ⬜ |
| 4 | Nov 30 - Dec 6 | Bash scripting and Git | ⬜ |
| 5 | Dec 7 - 13 | Docker | ⬜ |
| 6 | Dec 14 - 20 | Docker (images, Compose) | ⬜ |
| 7 | Dec 21 - 27 | Year-end break: practice and catch-up | ⬜ |
| 8 | Dec 28 - Jan 3 | Year-end break: Python, job-search prep | ⬜ |
| 9 | Jan 4 - 10 | AWS | ⬜ |
| 10 | Jan 11 - 17 | AWS | ⬜ |
| 11 | Jan 18 - 24 | AWS, Terraform basics | ⬜ |
| 12 | Jan 25 - 31 | Terraform | ⬜ |
| 13 | Feb 1 - 6 | Terraform, Day 90 retrospective | ⬜ |

Status key: ⬜ not started · 🟡 in progress · ✅ done

## Projects

| Project | What it shows | Status |
|---|---|---|
| [Capstone](projects/capstone/README.md) | My own app on AWS, fully automated: Terraform, Docker, Kubernetes, CI/CD, monitoring | ⬜ |

More projects are listed in [projects/](projects/README.md).

## How this repo is organized

```
notes/      one file per day (Problem / Solution / Lesson)
weekly/     Sunday recaps
labs/       hands-on exercises, one folder per lab (e.g. 01-linux-permissions)
projects/   bigger builds, including the capstone
docs/       runbooks, post-mortems, break/fix journal, diagrams, images
resources/  what helped me learn
scripts/    small automation scripts I write
```

## How to follow along

- Start with [notes/](notes/README.md) for the daily log.
- Read the [break/fix journal](docs/break-fix-journal.md) for the most honest part of the story.
- Weekly summaries are in [weekly/](weekly/).

## Security rules for this repo

This repo is public, so I would never commit:
- access keys, tokens, passwords, or `.env` files
- Terraform state files or `*.tfvars` with real values
- AWS account IDs or public IP addresses (I blur or replace them in screenshots)

A secret scan (Gitleaks) runs on every push as a safety net. If I ever leak a secret, I rotate it immediately instead of just deleting the commit.

## Resources

See [resources/](resources/README.md).

## License

[MIT](LICENSE). Notes and code are my own understanding. TS Academy course materials are not reproduced here.
