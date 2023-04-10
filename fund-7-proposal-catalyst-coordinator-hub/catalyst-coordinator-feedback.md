---
description: November and December 2021
---

# Catalyst-Coordinator-Feedback

Between November and December 2021 the Catalyst Coordinator Circle Representative trialed a [Catalyst-Coordinator-Feedback](https://github.com/Catalyst-Circle/Catalyst-Coordinator-Feedback) process to capture proposer concerns as GitHub issues.

This was later documented on this GitBook as part of the Fund 7 Catalyst Coordinator Hub proposal.

In all 26 issues were captured from mainly from [Coordinator Support insights](https://docs.google.com/spreadsheets/d/18pj3YhF-Mcq8xxOHgGz5YBOtV8FI0CEA82FC7b6G8qg/edit#gid=0) with the rest from social media sources (mainly Catalyst Coordinator Telegram).&#x20;

| Issue                                                                                                                                                            | Description                                                                                                                                                   |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1) [Good Practice ? One Wallet per Proposal](https://github.com/Catalyst-Circle/Catalyst-Coordinator-Feedback/issues/1)                                          | <p>Use a separate Wallet for each separately funded Catalyst project.</p><p>Raised by Peter Van Garderen</p>                                                  |
| 2) [Good Practice ? Convert your Catalyst ADA to stablecoin/fiat](https://github.com/Catalyst-Circle/Catalyst-Coordinator-Feedback/issues/2)                     | <p>Convert your Catalyst ADA to stablecoin/fiat as soon as you receive it if you need to pay project expenses in fiat.</p><p>Raised by Peter Van Garderen</p> |
| 3) [Open sourcing / availability of Atala PRISM API / SDK](https://github.com/Catalyst-Circle/Catalyst-Coordinator-Feedback/issues/3)                            | Open sourcing / availability of Atala PRISM API / SDK - Maury Shenk                                                                                           |
| 4) [Possible paths to open investments](https://github.com/Catalyst-Circle/Catalyst-Coordinator-Feedback/issues/4)                                               | Possible paths to open investments to the project outside catalyst to be able to continue development                                                         |
| 5) [Contact with the IOG wallet lite UX team](https://github.com/Catalyst-Circle/Catalyst-Coordinator-Feedback/issues/5)                                         | Contact with the IOG wallet lite UX team. - Niels Kijf                                                                                                        |
| 6) [Detailed receipts](https://github.com/Catalyst-Circle/Catalyst-Coordinator-Feedback/issues/6)                                                                | Detailed receipts of payouts, amounts, for which proposal to help with accounting. - Nori                                                                     |
| 7) [Wada core costs covered](https://github.com/Catalyst-Circle/Catalyst-Coordinator-Feedback/issues/7)                                                          | Wada core costs covered so Wada can focus on supporting and mentoring new projects. It's tough doing our own projects and supporting others - WADA            |
| 8) [Looking forward to have Cardano build a platform where investors can fund startu](https://github.com/Catalyst-Circle/Catalyst-Coordinator-Feedback/issues/8) | Looking forward to have Cardano build a platform where investors can fund startups (ie. Seed or A round) with ADA. - Yong Yang See Tho                        |

## GitHub CLI

For documentation on the GitHub Command Line Interface see here [https://cli.github.com/](https://cli.github.com/)

<figure><img src="../.gitbook/assets/Screenshot from 2023-04-09 17-09-46.png" alt=""><figcaption><p>Logging into a GitHub account using gh</p></figcaption></figure>

### Clone repo

<figure><img src="../.gitbook/assets/Screenshot from 2023-04-09 17-48-56.png" alt=""><figcaption></figcaption></figure>

### List Issues in repo

<figure><img src="../.gitbook/assets/Screenshot from 2023-04-09 17-57-40.png" alt=""><figcaption></figcaption></figure>

### Export issues to a csv file

`gh issue list --limit 1000 --state all | tr ',' ' ' | tr '\t' ',' > issues.csv`

### Extending GitHub CLI with hub

**hub** is _an extension to command-line git_ that helps you do everyday GitHub tasks without ever leaving the terminal.

{% embed url="https://hub.github.com/" %}

### How to create a PAT token (Personal Access Token)

See [https://quality-assurance-dao.gitbook.io/treasury-advisory-service/project-automation/general-introduction/pat-token](https://quality-assurance-dao.gitbook.io/treasury-advisory-service/project-automation/general-introduction/pat-token)
