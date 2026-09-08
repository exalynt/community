# Contributing to Exalynt

Thank you for your interest in contributing to Exalynt.

Exalynt is built around the idea that excellent software comes from thoughtful engineering, continuous improvement, and sharing what we learn with others.

Contributions of all sizes are welcome.

## Ways to Contribute

Contributing isn't limited to writing code. You can help by:

- Reporting bugs
- Suggesting features
- Improving documentation
- Adding or improving tests
- Improving examples
- Fixing bugs
- Improving developer experience
- Reviewing pull requests
- Participating in discussions
- Sharing experience using Exalynt projects

## Before You Start

Each Exalynt repository may have its own development instructions, architecture, conventions, and requirements.

Before making a contribution:

1. Read the repository's `README.md`.
2. Check for repository-specific contribution instructions.
3. Search existing issues and pull requests.
4. Review the project's license.
5. For significant changes, discuss the idea with maintainers first.

You generally don't need prior approval for small, straightforward fixes.

For larger features, architectural changes, new dependencies, breaking API changes, or significant refactoring, please open an issue or discussion before beginning implementation.

This helps make sure everyone agrees on the problem and general direction before significant work is invested.

## Issues

### Bug Reports

A useful bug report should include, when applicable:

- What happened
- What you expected to happen
- Steps to reproduce the problem
- Relevant versions
- Operating system or environment
- Configuration involved
- Logs or error messages
- A minimal reproduction

Please remove credentials, secrets, private data, and other sensitive information before posting.

### Feature Requests

Feature requests should focus first on the problem being solved.

Describe:

- The problem or limitation
- The use case
- Why solving it would be useful
- Any constraints that should be considered

You're welcome to suggest a solution, but defining the problem clearly is often more valuable than prescribing a particular implementation.

## Pull Requests

### Keep Changes Focused

Prefer pull requests that solve one clearly defined problem.

Focused changes are easier to:

- Understand
- Review
- Test
- Merge
- Revert if necessary

Avoid combining unrelated refactoring or cleanup with a functional change unless it is necessary to implement the change.

### Write for the Next Engineer

Code should optimize for understanding and maintainability, not cleverness.

Prefer:

- Clear names
- Simple designs
- Small, understandable abstractions
- Explicit behavior
- Consistency with the existing codebase

Complexity should have a reason to exist.

### Tests

Changes should include appropriate tests when practical.

Bug fixes should ideally include a test demonstrating the failure and preventing regression.

New behavior should test the important expected behavior rather than implementation details.

### Documentation

If your change affects how users interact with a project, update the relevant documentation.

This can include:

- README content
- API documentation
- Examples
- Configuration documentation
- Migration instructions
- Comments where behavior isn't obvious

### Commit History

Keep commits reasonably focused and understandable.

Maintainers may squash commits when merging a pull request, so contributors should not feel obligated to create a perfect commit history before submitting useful work.

### Pull Request Description

Your pull request should clearly explain:

- What changed
- Why the change is needed
- Important implementation decisions
- How the change was tested
- Any breaking changes or migration considerations

Link the relevant issue when one exists.

## Compatibility and Breaking Changes

Public APIs should be changed deliberately.

When modifying an existing public API, consider whether the change:

- Breaks existing consumers
- Changes established behavior
- Requires migration
- Can be introduced in a backward-compatible way

Breaking changes may sometimes be the correct engineering decision, but they should be intentional and clearly communicated.

Individual projects may define their own compatibility and versioning policies.

## Dependencies

New dependencies introduce long-term maintenance, security, compatibility, and supply-chain considerations.

Before adding a dependency, consider:

- Whether the functionality is substantial enough to justify it
- Whether the project is actively maintained
- Its license
- Its security history
- Its transitive dependencies
- Whether the functionality can reasonably be implemented without it

This doesn't mean dependencies should be avoided. It means they should earn their place.

## Code Review

Code review is collaboration, not competition.

Reviewers should focus on the code and engineering decisions rather than the person who wrote them.

Contributors should expect questions and requested changes. Reviewers should explain the reasoning behind significant requests whenever practical.

Disagreement is normal and often useful.

When there are multiple reasonable approaches, maintainers ultimately need to choose the direction that best fits the goals and philosophy of the project.

## AI-Assisted Contributions

Using AI-assisted development tools is welcome.

Contributors remain responsible for everything they submit.

Before submitting AI-assisted code, make sure you:

- Understand the code
- Verify that it is correct
- Test it appropriately
- Ensure it follows project conventions
- Review it for unnecessary complexity
- Verify that it does not introduce licensing or intellectual-property problems
- Remove generated code that isn't actually needed

"I didn't write it; the AI did" doesn't change responsibility for a contribution.

## Security

Do not publicly disclose vulnerabilities that could put users or deployed systems at risk.

Check the affected repository for a `SECURITY.md` file and follow its reporting instructions when available.

Never include credentials, tokens, private keys, customer information, or other sensitive data in issues or pull requests.

## Licensing

By contributing to an Exalynt project, you agree that your contribution may be distributed under that project's license.

Always review the repository's `LICENSE` file before contributing.

## Community Conduct

All contributors are expected to follow the Exalynt [Code of Conduct](CODE_OF_CONDUCT.md).

Technical disagreement is welcome.

Personal attacks, harassment, intimidation, and disrespectful behavior are not.

## Questions

If you're unsure where to start, open a GitHub Discussion.

You don't need to understand the entire project before contributing. Asking good questions, identifying confusing behavior, and improving something small are excellent ways to get involved.

Thank you for helping make Exalynt better.
