# baymax-renovate-config

## Config Rules

| Dep Group                                 | Schedule                   | Automerge? |
| ----------------------------------------- | -------------------------- | ---------- |
| Pin dependency                            | Weekday                    | Yes        |
| npm runtime dependency and peerDependency | Every Monday               | No         |
| npm devDependency                         | Every Tuesday              | Yes        |
| Buildkite plugin                          | Every 2 weeks on Wednesday | Yes        |
| Gantry                                    | Every 2 weeks on Wednesday | Yes        |
| Docker image                              | Every 2 weeks on Wednesday | No         |
| Lock file maintenance                     | Every 2 weeks on Wednesday | Yes        |
| Noisy dependency                          | Every 1st day of month     | No         |

Note that:

- All `major` updates are ignored. Only `minor` and `patch` updates are processed.
