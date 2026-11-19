# IT211-Event-Entry-System
Shared repository for the IT211 Event Entry System project, including source code, UML diagrams, and documentation.



Git Workflow and Team Conventions

1. Branching Convention

- `main` - Stable and final version of the project.
- `develop` - Main development branch where completed features are combined.
- `feature/feature-name` - Used when developing new features.
- `fix/bug-name` - Used when fixing bugs.

Branching Rules
1. Do not commit directly to `main`.
2. Create a separate branch for each assigned feature or bug fix.
3. Push your changes to your own branch.
4. Create a Pull Request to merge changes into `develop`.
5. Review and test changes before merging.
6. Only approved and tested changes should be merged into `main`.

2. Commit Message Convention

Use the following format:

`type: short description`

Commit types:

- `feat:` - Adding new features.
- `fix:` - Fixing bugs.
- `docs:` - Updating documentation.
- `diagram:` - Adding or updating UML diagrams.
- `refactor:` - Improving existing code.
- `test:` - Adding or updating tests.
- `chore:` - Repository maintenance.

Commit Message Examples

- `feat: add login functionality`
- `fix: correct event registration error`
- `docs: update project README`
- `diagram: add class diagram`
- `chore: create project folders`

3. Team Collaboration Rules

1. Every member must clone the shared repository.
2. Every member must work using their assigned branch.
3. Pull the latest changes before starting new work.
4. Commit changes using the agreed commit message format.
5. Push changes to GitHub regularly.
6. Use Pull Requests for reviewing and merging contributions.
