# vibepg

**Vibe-ready local PostgreSQL for rapid prototyping.**

vibepg is a lightweight Rust CLI designed to manage local PostgreSQL
databases during fast development and experimentation. It allows
developers to spin up isolated Postgres instances in seconds, manage
credentials automatically, and focus purely on building.

Built specifically for local prototyping and vibe coding workflows,
vibepg removes the friction of manual database setup. No need to install
PostgreSQL or manage passwords yourself --- everything runs inside
Docker and credentials are handled securely within the tool.

vibepg provides:

-   Fast spin-up of local PostgreSQL instances
-   Persistent or ephemeral database modes
-   Natural language--style commands
-   Built-in credential generation and secure storage
-   Clean lifecycle management (start, stop, remove)
-   SQL execution and data import capabilities
-   Full isolation via Docker containers
-   Cross-platform reliability powered by Rust

vibepg is intentionally local-first and prototype-focused. It is not
intended for production database hosting or remote orchestration.
Instead, it is built for developers who need a database instantly while
experimenting, testing ideas, or building features.

Docker is required, as vibepg depends on containerized PostgreSQL
instances. No local Postgres installation is needed.

Written in Rust for speed, safety, and simplicity.
