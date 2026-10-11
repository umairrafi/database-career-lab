        # Database Career Lab

        Project-based interview prep aligned to [career-lab-master-plan](https://github.com/umairrafi/muhammad-umair-portfolio/blob/main/docs/career-lab-master-plan.md) and [complete catalog](https://github.com/umairrafi/muhammad-umair-portfolio/blob/main/docs/career-lab-complete-catalog.md).

        ## Who this is for

        - Backend engineers building public proof for job switch (UAE/GCC — 25k AED framing in master plan §6)
        - Developers mapping **engineering-profile** evidence to buildable labs (no employer secrets)

        ## Prerequisites

        MySQL locally or Docker

        ## Capstone: SchemaStream

        Evolving codebase in [`capstone/schema-stream/`](capstone/schema-stream/) — run instructions in capstone README.

        ## Roadmap

        | Week | Topic | Folder | Objective |
        |------|-------|--------|-------------|
        | **1** | Relational modeling | [week-01-relational-modeling](weeks/week-01-relational-modeling/) | Orders/payments/share_offer analog |
| **2** | Forward migrations | [week-02-forward-migrations](weeks/week-02-forward-migrations/) | Forward-only scripts |
| **3** | Atlas validate/lint CI | [week-03-atlas-ci](weeks/week-03-atlas-ci/) | PR gate pattern |
| **4** | Index + EXPLAIN | [week-04-index-explain](weeks/week-04-index-explain/) | §10 gap #5 |
| **5** | Idempotent backfill | [week-05-idempotent-backfill](weeks/week-05-idempotent-backfill/) | DML backfills |
| **6** | Capstone bundle | [week-06-capstone-bundle](weeks/week-06-capstone-bundle/) | Multi-schema migration tarball |

        ## Weekly structure

        ```
        week-NN-slug/
        ├── README.md
        ├── 01-lessons/
        ├── 02-hands-on/
        ├── 03-exercises/
        └── 04-capstone-project/
        ```

        ## Start here

        ```bash
        cd weeks/week-01-relational-modeling
        cat README.md
        ```

        ---

        Built by [Muhammad Umair Virk](https://muhammad-umair.pages.dev) · Backend · UAE
