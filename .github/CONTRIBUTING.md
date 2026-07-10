# Contributing

## Prerequisites

Before you spend valuable time contributing to this project, please first
discuss the change you wish to make with its maintainers. A list of maintainers
can be found in the package metadata file - for example, `Cargo.toml`,
`package.json`, or `pyproject.toml` - or `CODEOWNERS`. While we would prefer you
file an issue to keep communication open and transparent, you may also reach out
by email.

Next, ensure your environment is prepared. Check the README for guidance on
language-specific tooling, but note that either [Nix] or the project package
manager should install the relevant development programs automatically. Please
use these designated linters and formatters to keep your contributions
consistent with the existing codebase.

If your environment has generative artificial intelligence tools, refer to
the [Generative Tools Policy section] for further information.

[Nix]: https://nixos.org
[Generative Tools Policy section]: #Generative-Tools-Policy

## Workflow

1. Fork and clone this repository.
2. Create a new branch in your fork based off the **main** branch.
3. Make your changes.
4. Commit your changes, and push them.
5. Submit a pull request.

## Standard of Work

### Licensing

We use the [MIT license] for our open-source projects. While most licenses are
compatible with the MIT license, we must be certain that portions of software
are compatible before we can legally incorporate or vendor them. For this
reason, we discourage adding dependencies using the GPL family of licenses, but
we will permit them if they are the best available solution.

[MIT license]: https://opensource.org/license/mit

### Generative Tools Policy

Due to moral, philosophical, environmental, and quality concerns, contributions
must not include *any* content produced wholly or partially by generative or
probabilistic systems, particularly large language models. This includes the
project itself, its documentation, contents and metadata of commits to it,
communications surrounding it, and all other related channels.

### Design

Our design philosophy is chiefly inspired by the [UNIX philosophy] of simple and
modular programs. Each project should aspire to do one thing well, rather than
evolving to become an entire system of its own. Some features will be deemed
out-of-scope for this project, and that's okay - they will likely be better
placed elsewhere, and keeping our projects light allows them to be as useful as
possible.

[UNIX philosophy]: https://harmful.cat-v.org/cat-v/unix_prog_design.pdf

## Code of Conduct

Please refer to our [Code of Conduct] for guidelines on interacting with our
projects and their respective communities.

[Code of Conduct]: https://radicle.network/nodes/rad.kludgecs.com/rad:z2gJsz87p85eSNWV25zXJGgerYhh9/tree/.github/CODE_OF_CONDUCT.md
