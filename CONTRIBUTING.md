# Contributing to al-folio

Thank you for considering contributing to al-folio!

## Pull Requests

We welcome your pull requests (PRs).
For minor fixes (e.g., documentation improvements), feel free to submit a PR directly.
If you would like to implement a new feature or fix a bug, please make sure an appropriate issue exists first and mention it in your PR.

Note that since [#2048](https://github.com/alshedivat/al-folio/pull/2048) al-folio uses the [Prettier formatter](https://prettier.io/) for its code. All new submitted code must conform to its standard. If you don't have `prettier` installed and the Prettier check fails in CI, check the failed action in our repo — there will be an artifact with an HTML diff showing the needed changes.

### Adding new social media information

To add new social media information, you might need to modify several places. The template supports icons from Academicons, Font Awesome, and Tabler Icons. For an example PR, see "Add HAL id to socials".

- `\_data/socials.yml` — your social media information
- `\_includes/metadata.liquid` — add social media information to site metadata
- `\_includes/social.liquid` — where the social media icon will be displayed
- `\_scripts/search.liquid.js` — make the social media information appear in search

## Issues

We use GitHub issues to track bugs and feature requests. Before submitting an issue, please make sure:

1. You have read the FAQ (see `FAQ.md` or the README) and your question is NOT addressed there.
2. You have done your best to ensure the issue is NOT a duplicate of previous issues.
3. Your issue is either a bug (unexpected/undesirable behavior) or a feature request. If it is just a question, please ask it in the Discussions forum.

When submitting an issue, please use the appropriate template.

## License

By contributing to al-folio, you agree that your contributions will be licensed under the `LICENSE` file in the root directory of the repository.
