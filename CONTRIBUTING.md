# Contribution Guidelines

Thanks for your interest in `awesome-field-service`. This list exists to help service businesses, developers, and analysts find production-ready tools and resources in the field service management (FSM), CMMS, and service operations space.

## What we accept

- **Commercial FSM platforms** with active development and existing customers (no abandoned products, no vaporware).
- **Open source FSM/CMMS** projects with commits within the last 12 months.
- **APIs and integrations** that are publicly documented and actively maintained.
- **Reports and studies** with verifiable authorship (analyst firms, peer-reviewed research, vendor reports clearly marked).
- **Books, blogs, podcasts** that are actively published and substantive (no thin SEO blogs).
- **Communities** with active moderation and at least 1,000 members.

## What we reject

- Affiliate links or referral codes.
- Marketing copy disguised as descriptions ("the best", "the leading", "revolutionary").
- Tools that have been abandoned (no commits or releases for 18+ months unless they are stable utilities).
- Personal blogs without consistent publishing history.
- Listings that exist only to promote the contributor's own product without adding value.
- Closed-source tools without a working free tier or trial.

## Format requirements

Every entry follows this exact format:

```markdown
- [Tool name](https://example.com) - Short description ending with a period.
```

**Rules:**

1. **Tool name** in title case. Match how the vendor writes it.
2. **URL** must be the canonical site (no UTM tags, no tracking parameters).
3. **Description** between 30 and 120 characters. Start with a capital letter. End with a period.
4. Do **not** start the description with "is", "a", or "an" — make it informative.
5. Alphabetical order within each section (case-insensitive).
6. Place new sections only if you have **3+ entries** that belong there.

**Good example:**

```markdown
- [Jobber](https://getjobber.com) - User-friendly FSM for SMB service businesses, strong onboarding.
```

**Bad examples:**

```markdown
- [Jobber](https://getjobber.com?ref=me) - Is the BEST FSM for everyone, revolutionary platform. ← affiliate link + marketing copy
- [My Cool Tool](https://example.com) - Cool. ← description too short, useless
- [SomeTool](https://example.com) ← missing description entirely
```

## Section placement

If you are unsure where an entry belongs:

- **Commercial Platforms** is split by company size — Enterprise (1000+ employees), Mid-market (50-1000), SMB (<50).
- **Danish & Nordic Platforms** is for vendors headquartered or primarily serving Denmark, Sweden, Norway, Finland, Iceland.
- **Open Source FSM & CMMS** is for projects with an OSI-approved license.
- **Integrations & APIs** is for headless tools you wire into another system. Not standalone products.

## How to submit

1. Fork this repository.
2. Edit `README.md` and add your entry in the correct alphabetical position within the correct section.
3. Verify your entry passes `awesome-lint` if you have it installed (`npm install -g awesome-lint && awesome-lint`).
4. Commit with a clear message: `Add [Tool Name] to [Section]`.
5. Open a pull request from your fork.
6. In the PR description, briefly explain why this tool belongs on the list.

## Self-promotion

You **may** submit your own tool — but be honest:

- Disclose that you are affiliated with the tool in the PR description.
- Describe it neutrally. The community is sharp; marketing speak gets rejected.
- The tool must have at least 5 publicly-known customers or 50+ stars (if OSS).

## Review process

We aim to review pull requests within **7 days**. Larger structural changes (new sections, reorganizations) may take longer to discuss.

If your PR is rejected, we will explain why so you can resubmit if appropriate.

## License

By contributing, you agree that your contributions will be licensed under [CC0 1.0 Universal](LICENSE) — the same license as the list itself.

---

Maintained by [FieldService](https://fieldservice.dk).
