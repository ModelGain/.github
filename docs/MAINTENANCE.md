# Organization profile maintenance

## Ownership and source of truth

- GitHub organization overview: https://github.com/ModelGain
- Public display source: [`profile/README.md`](../profile/README.md)
- Canonical published-product status and descriptions: https://modelgain.com/products/
- Actual distribution status: the corresponding WordPress.org plugin listing or other official release page.

The GitHub overview is a curated directory, not a parallel product database. Changes to product availability or positioning must first be verified against the public website and distribution channel.

## Updating the profile

1. Verify every new product is publicly accessible and that any claimed release has an actual distribution link.
2. Update `profile/README.md` with concise descriptions, supported links, and a clear development/release distinction.
3. Confirm URLs return valid responses and the organization Overview actually renders the content.
4. Review the rendered Markdown on desktop and narrow screens; avoid fragile badges, dynamic statistics, or image dependencies.
5. Revisit the page after significant product launches or approximately once per quarter. Do not promise an automated synchronization that has not been implemented.

## Organization-level configuration

- The repository must be named exactly `.github`, be **public**, and contain `profile/README.md`.
- Set the organization's Website to `https://modelgain.com/`.
- Organization owners can optionally pin up to six publicly visible product repositories. Never publish an internal repository solely to fill the pinned area.
- This public profile is not proof that every ModelGain product has an open-source GitHub repository.
- Do not include direct email addresses until the associated mailbox or alias is configured and confirmed.

## Lightweight acceptance checks

- Anonymous visitor can load `https://github.com/ModelGain` and see the headline and product table.
- Anonymous visitor can load `https://github.com/ModelGain/.github/blob/main/profile/README.md`.
- All first-party links point to `modelgain.com`; plugin installation links point to their official WordPress.org directory entries.
- No sensitive files or credentials exist in this repository; only the three intended Markdown files are versioned.
