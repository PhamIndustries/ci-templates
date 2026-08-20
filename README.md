# Moved → [`PhamIndustries/ci-infrastructure`](https://github.com/PhamIndustries/ci-infrastructure)

This repository is **retired**.

| Was | Now |
|-----|-----|
| `PhamIndustries/ci-templates` | **`PhamIndustries/ci-infrastructure`** |
| `uses: …/ci-templates/.github/workflows/python-uv-ci.yml@v1` | `uses: PhamIndustries/ci-infrastructure/.github/workflows/python-uv-ci.yml@v1` |
| Local `~/Projects/ci-templates` | `~/Projects/ci-infrastructure` |

**Agents:** start at [`ci-infrastructure/agent/README.md`](https://github.com/PhamIndustries/ci-infrastructure/blob/main/agent/README.md).

The reusable workflow file here may remain briefly for leftover pins; **do not** add features. All SoT edits go to **ci-infrastructure**.
