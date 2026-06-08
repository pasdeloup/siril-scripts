# Contributing to Naztronomy Siril Scripts

Thank you for your interest in contributing! This document covers everything you need to know before submitting a pull request or opening an issue.

---

## I Want To Contribute

> ### Legal Notice <!-- omit in toc -->
>
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the project licence.

## How to Contribute

Pull requests are welcome! To keep the review process smooth, please follow the guidelines below before submitting.

- **All pull requests must target the `develop` branch.** Do not open PRs against `main` directly.
- **Bug fixes** and **new features** will be reviewed before merging.
- **New features must be non-breaking.** All existing functionality must continue to work as expected after your change. PRs that regress existing behavior will not be accepted until resolved.
- For significant changes, open an issue first to discuss the approach.
- Keep pull requests focused — one feature or fix per PR.

---

## Code Style

- Follow the existing code style found throughout the scripts.
- Use clear, descriptive variable names.
- Commit messages should be descriptive. It's good practice to commit often to preserve history of small changes.
- Keep UI dialogs and prompts consistent with the existing PyQt6 patterns used in the scripts.
- Do not introduce dependencies beyond what is already used (`PyQt6`, `numpy`, `astropy`) unless discussed in an issue first.

---

## Testing Requirements

Before submitting a pull request, ensure your changes have been tested:

- **Run the affected script end-to-end** with real data (light frames, optional calibration frames) to verify it completes without errors.
- **Test on the platform(s) relevant to your change.** Cross-platform fixes should be tested on at least two platforms when possible.
- **Test edge cases** when possible.
- **Log only relevant information and nothing more**
- Update any relevant documentation or in-script help text if behavior changes.

---

## Licensing & Attribution

This project is licensed under the **GNU General Public License v3.0 or later** (GPL-3.0-or-later). See the [LICENSE](LICENSE) file for the full license text.

By submitting a pull request, you agree that your contribution will be licensed under the same GPL-3.0-or-later license as the rest of this project.

### Attribution

- **Original author:** Nazmus Nasir — [Naztronomy](https://www.naztronomy.com)
- Contributors are credited through Git commit history.
- Do not remove or alter existing copyright notices or attribution headers in source files.
- If your contribution incorporates code or algorithms from a third-party source, you must clearly document the source and confirm the license is compatible with GPL-3.0-or-later.

---

## AI Disclosure

This project welcomes contributions that were assisted or drafted with the help of AI tools (e.g., GitHub Copilot, ChatGPT, Claude, or similar). However, the following requirements apply to all AI-assisted contributions:

- **You are responsible for the code you submit.** Review all AI-generated code carefully before including it in a PR. Do not submit output you have not read and understood.
- **Disclose AI assistance in your PR description.** If any portion of your contribution was generated or significantly shaped by an AI tool, note this in the pull request. Example: _"Parts of this implementation were drafted with GitHub Copilot and reviewed/modified by me."_
- **Verify correctness.** AI tools can produce plausible-looking but incorrect astronomy logic, incorrect Siril API usage, or subtle bugs. Test thoroughly (see Testing Requirements above).
- **No AI-generated code without human review.** Unreviewed, wholesale AI output will not be accepted.
- **License compliance.** Ensure any AI-assisted code does not inadvertently reproduce copyrighted third-party code in a way that conflicts with GPL-3.0-or-later.

---

## Reporting Bugs & Requesting Features

- Open an issue in the [issues forum](../../issues).
- For bugs, include: OS, Siril version, Python version, telescope model, and steps to reproduce.
- For feature requests, describe the use case and how it fits the existing workflow.

You can also reach the maintainer through:

- [Discord community](https://discord.gg/yXKqrawpjr)
- YouTube comments on the [demo videos](https://www.youtube.com/naztronomy)
