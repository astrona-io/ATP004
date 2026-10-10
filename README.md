# ATP004 — Certified Cloud Native Platform Engineer (CNPE)

An Astrona **training path**: a course track that groups training series
(`ATSxxx`) as its domains. Each stage in `path.yaml` is one exam domain and
points at the repository that teaches it:

| Stage | Domain | Weight | Content |
| --- | --- | --- | --- |
| STG001 | Platform Architecture and Infrastructure | 15 % | [ATS017](https://github.com/astrona-io/ATS017) |
| STG002 | GitOps and Continuous Delivery | 25 % | [ATS018](https://github.com/astrona-io/ATS018) |
| STG003 | Platform APIs and Self-Service Capabilities | 25 % | [ATS019](https://github.com/astrona-io/ATS019) |
| STG004 | Observability and Operations | 20 % | [ATS020](https://github.com/astrona-io/ATS020) |
| STG005 | Security and Policy Enforcement | 15 % | [ATS021](https://github.com/astrona-io/ATS021) |

The site picks it up through [astrona-content](https://github.com/astrona-io/astrona-content):
`courses/certified-cloud-native-platform-engineer-cnpe.yaml` points at this
repository, and the content sync builds the course — one section per stage,
with the readings and labs each stage repository lists in its `astrona.yaml`.
