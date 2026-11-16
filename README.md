# irie-people.github.io

The home page of Irie People: [Irie](https://github.com/irie-people/irie), [Riddim](https://github.com/irie-people/riddim) and [Steak](https://github.com/irie-people/steak). GitHub Pages serves this repository at the org's root, <https://irie-people.github.io/>, and each project's own site beneath it at `/irie/`, `/riddim/` and `/steak/`. A custom domain set on this site carries the project sites with it.

It is plain HTML and one stylesheet, with no build step. GitHub Pages publishes `main` as it is, and `.nojekyll` keeps Jekyll out of the way.

## Working on it

- Nothing here may identify a person: no names, usernames, emails, home paths or hostnames. Use `alice` and `example.com`.
- Build from public documentation and list each source in [PROVENANCE.md](PROVENANCE.md).
- Commit in UTC with sign-off, `TZ=UTC git commit -s`, under a [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) subject.
- The page draws from [Roots](https://github.com/irie-people/roots), Irie People's design library, as Irie's site does: its colours are Roots' Evergreen roles, between `design:` comments in `style.css`, and its parts follow Roots' components. Change a colour in Roots, then copy the two blocks from Irie's `site/style.css`, which Irie's `tools/design.sh` keeps in step with the library.
- The `.family` rules, the links between the sites, are the same in this stylesheet and in Irie's, Riddim's and Steak's. Change all four together.
- `preview.png`, the picture link previews show, is drawn from Irie's `docs/preview.html` with `#people`; that page says how. Draw it again when the headline changes.

## License

[Apache-2.0](LICENSE).
