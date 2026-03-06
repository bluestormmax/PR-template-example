## Summary
<!-- What problem does this solve? Why is this change being made? -->


## Linked ticket / issue
<!-- URL or issue number. PRs without a linked ticket may be sent back. -->


## Type of change
- [ ] Bug fix
- [ ] New feature / enhancement
- [ ] Refactor / cleanup (no behavior change)
- [ ] Chore (dependencies, config, CI/CD, tooling)
- [ ] Content / copy update
- [ ] Breaking change *(describe impact below)*

## Approach
<!-- Briefly explain how you solved it. Mention any alternatives you considered and why you went this direction. -->


## How to test
<!-- Step-by-step instructions a reviewer can follow on their own. Include env setup if needed. -->
1. 
2. 
3. 

## Screenshots / recording
<!-- Required for any UI change. Before/after preferred. GIF or Loom for interactive changes. -->

| Before | After |
|--------|-------|
|        |       |

## Review notes
<!-- Anything you want the reviewer to pay special attention to, known edge cases, or areas of uncertainty. -->
<!-- Use conventional comment labels in your review: suggestion: / question: / issue: / nitpick: / praise: -->


## Checklist

**Author**
- [ ] Self-reviewed before requesting review
- [ ] No `console.log`, `var_dump`, or debug code left in
- [ ] Linting / PHPCS / ESLint passes locally
- [ ] Branch is up to date with `main` / `trunk`
- [ ] Tests added or updated *(if applicable)*
- [ ] Environment variables or config changes documented in PR or ticket

**Accessibility**
- [ ] New interactive elements are keyboard accessible
- [ ] Color contrast meets WCAG AA
- [ ] Images have appropriate alt text
- [ ] ARIA roles/labels added where needed

**WordPress-specific** *(if applicable)*
- [ ] User input is sanitized and escaped
- [ ] No direct database queries without `$wpdb` or appropriate abstraction
- [ ] Plugin/theme version bumped if shipping *(semver)*
- [ ] Tested against at least the last two major WP versions

**React/JS-specific** *(if applicable)*
- [ ] No unnecessary re-renders introduced
- [ ] PropTypes or TypeScript types updated
- [ ] No new bundle size regressions worth flagging
