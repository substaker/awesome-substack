# Contributing to Awesome Substack

First off, thanks for taking the time to contribute! 🎉

This is a community-driven project and we love receiving contributions from people like you. Whether it's a new Substack recommendation, a tool, a resource, or a bug fix — every contribution makes this list better for everyone.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Adding a Substack Newsletter](#adding-a-substack-newsletter)
- [Adding a Tool or Resource](#adding-a-tool-or-resource)
- [Suggesting a New Category](#suggesting-a-new-category)
- [Reporting Issues](#reporting-issues)
- [Pull Request Process](#pull-request-process)
- [Style Guide](#style-guide)
- [Quality Standards](#quality-standards)

---

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/). By participating, you are expected to uphold this code. Please report unacceptable behavior by opening an issue.

## How Can I Contribute?

There are several ways you can contribute to Awesome Substack:

- **Add a new Substack** — Know an amazing publication that's missing? Submit it!
- **Add a tool or resource** — Found a useful tool for readers or writers? Let us know.
- **Suggest a new category** — Think we're missing an entire topic area? Propose one.
- **Fix broken links** — Spotted a dead link or incorrect URL? Help us fix it.
- **Improve descriptions** — Think a description could be clearer or more accurate? Submit an edit.
- **Remove inactive Substacks** — If a publication hasn't posted in 6+ months, flag it for removal.

## Adding a Substack Newsletter

Before submitting a new Substack, please make sure it meets the following criteria:

### Requirements

- [ ] The Substack is **actively publishing** (at least one post in the last 3 months).
- [ ] The Substack has a **meaningful body of work** (at least 10 published posts).
- [ ] The content is **high quality** — well-written, insightful, or uniquely valuable.
- [ ] The Substack is **not already on the list** — please search the document first.
- [ ] The Substack is **not primarily promotional** — it should provide genuine value to readers, not just market a product or service.
- [ ] The Substack is available in **English** (non-English Substacks may be considered for future internationalization).

### How to Add

1. Fork this repository.
2. Find the appropriate category in `awesome-substack.md`.
3. Add your entry in the correct position (see [Style Guide](#style-guide)).
4. Submit a pull request with a brief explanation of why the Substack belongs on the list.

### Entry Format

Each entry should follow this exact format:

```
- [Newsletter Name](https://example.substack.com/) - A concise, informative description of what the newsletter covers and why it's worth reading.
```

**Rules:**

- Use the official name of the publication.
- Link to the Substack homepage (not a specific post).
- Description must start with a capital letter.
- Description must end with a period.
- Description should be one to two sentences (max ~30 words).
- Do not use promotional language like "the best" or "must-read" (unless quoting a notable source).
- Do not include subscriber counts in the description (these change frequently).

## Adding a Tool or Resource

Tools and resources are welcome if they meet the following criteria:

### Requirements

- [ ] The tool or resource is **directly relevant** to the Substack ecosystem (readers, writers, or publishers).
- [ ] The tool is **currently functional** and accessible.
- [ ] The tool is **not a direct competitor** trying to use this list for self-promotion (Substack alternatives section is an exception).
- [ ] Free tools are preferred; paid tools should be clearly noted or offer a free tier.

### Entry Format

```
- [Tool Name](https://example.com/) - A concise description of what the tool does and who it's for.
```

## Suggesting a New Category

If you think a new category is needed:

1. Open an issue with the title: `[Category Proposal] Your Category Name`.
2. Include a brief description of what the category would cover.
3. List at least **3 Substacks** that would belong in this category and don't fit well in existing ones.
4. The maintainers will review and discuss before approving.

## Reporting Issues

Use GitHub Issues to report:

- **Broken links** — Title: `[Broken Link] Newsletter Name`
- **Inactive Substacks** — Title: `[Inactive] Newsletter Name` (include the date of the last post if possible)
- **Incorrect information** — Title: `[Correction] Newsletter Name`
- **Duplicate entries** — Title: `[Duplicate] Newsletter Name`
- **Spam or low-quality entries** — Title: `[Quality] Newsletter Name`

## Pull Request Process

1. **Fork** the repository and create a new branch from `main`.
2. **Make your changes** following the [Style Guide](#style-guide).
3. **Test your links** — make sure all URLs resolve correctly.
4. **Submit the PR** with a clear title and description.
5. **Wait for review** — maintainers will review your PR and may request changes.
6. **One approval** from a maintainer is required before merging.

### PR Title Format

Use one of the following prefixes:

- `Add: [Newsletter/Tool Name]` — for new additions
- `Remove: [Newsletter/Tool Name]` — for removals
- `Fix: [description]` — for broken links or corrections
- `Update: [description]` — for description improvements
- `Category: [Category Name]` — for new categories

### Example PR Description

```
## What I'm Adding

- **Name:** The Example Newsletter
- **URL:** https://example.substack.com/
- **Category:** Technology & Software Engineering
- **Why it belongs:** The author is a former Google engineer who writes deeply
  technical posts about distributed systems. The newsletter has 50+ posts and
  publishes weekly.
```

## Style Guide

### Ordering

- Entries within each category should be placed based on relevance and notability. New additions typically go at the end of their category unless there's a strong reason otherwise.
- Categories in the Table of Contents should match the order of categories in the document.

### Formatting

- Use `##` for main category headings.
- Use `-` (hyphen) for list items, not `*` (asterisk).
- One blank line between each category section.
- No trailing whitespace.
- No markdown tables.
- No emojis in entry descriptions (keep it clean and professional).
- Links should use HTTPS where available.

### Descriptions

- Write in the **third person** (e.g., "Covers AI research" not "I cover AI research").
- Be **specific** about what the newsletter covers, not vague.
- Mention the **author's credentials** if they add credibility (e.g., "ex-Google engineer," "Pulitzer finalist").
- Avoid **subjective superlatives** unless directly quoting a notable source.

**Good:**
```
- [Example](https://example.substack.com/) - Weekly deep dives into distributed systems and cloud architecture by a former AWS principal engineer.
```

**Bad:**
```
- [Example](https://example.substack.com/) - The absolute best newsletter about tech stuff. A must-read!!!
```

## Quality Standards

We aim to keep this list high-quality and useful. Entries may be removed if:

- The Substack has not published in **6 or more months**.
- The content quality has **significantly declined**.
- The Substack has **pivoted** to a topic that no longer fits its category.
- The link is **permanently broken** and no alternative URL can be found.
- The publication has been **flagged by multiple community members** for low quality.

Maintainers perform periodic reviews to ensure the list stays current and valuable.

---

## Questions?

If you have any questions about contributing, feel free to open an issue with the `[Question]` prefix or start a discussion in the Discussions tab.

Thank you for helping make Awesome Substack better for everyone! ❤️