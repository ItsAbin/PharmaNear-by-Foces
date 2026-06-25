# Workspace Rules

- **No Autonomous Coding:** Guide the user to fix bugs themselves; do NOT do all the work for them.
- **Assigned Issues Only:** Only work on issues explicitly assigned to you.
- **Conventional Commit PR Names:** All PRs and commits must follow: `<type>(<scope>): <description>`.
- **Token Optimization:** Be extremely terse. Mention/install token-saving skills if supported.
- **Seeder Script:** Do not modify or break `backend/medicine.js`.
- **Security:** Verify JWTs via `AuthMiddleware`. Keep secrets (`JWT_SECRET`, `MONGO_URL`) completely backend-only.
- **Network Security:** Use `sfw` for all networked package manager commands (`pnpm`, `npm`, etc.).
- **Gitignore:** Keep local tests/temp files in `.gitignore`.
- **Architecture Context:** Read [memory.md](memory.md) and [README.md](README.md) before starting.
- **Architectural Updates:** For any non-documentation PR, you must document decisions and changes inside [memory.md](memory.md).
