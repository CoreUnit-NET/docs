# Standards
The rules for CoreUnit.NET developers and administrators.

## Formats
- **Time Zone:** Use UTC as the standard time zone for all date and time references.
- **Time Format:** Use the 24-hour format for all times and scheduling to avoid any confusion.

## Version Control
- **Version Control:** Git
- **Workflow:** Use [Git-flow](https://www.atlassian.com/de/git/tutorials/comparing-workflows/gitflow-workflow) if you have parallel development on a repository, otherwise you can use the main branch.
- **Commit Message:** Commit messages should try to cover all the changes in a commit, but can be general.
- **Branches:** Is covered by the [Git-flow](https://www.atlassian.com/de/git/tutorials/comparing-workflows/gitflow-workflow), but you will mostly find yourself using the `main`, `develop` and `feature/*` branches.

## Technologies
- **Container Tool:** Docker
- **Operating System:** Ubuntu is the default Linux server disto *unless there is a compelling reason to choose an alternative*.

## Development
- **Testing:** Provide at least one E2E test.
- **Docs:** Every repo should have a README.md with an About, Getting Started and Development section.
- **Getting Started:** A Getting Started Guide should be kept up to date in each repository.
- **Giant files:** *Try to divide large files into smaller ones.*
