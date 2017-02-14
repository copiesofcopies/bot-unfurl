# Contributing to unfurl bot
:+1: First off, thanks for taking the time to contribute! :+1:

# Contributor License Agreement (CLA)
A CLA is a document that specifies how a project is allowed to use your
contribution.  We want a CLA that is simple and as clear as possible so that it
doesn't impede contributions to the unfurl bot project.

When you make a contribution to the unfurl bot project, you agree:

1. Your contribution is your original work (you own the copyright) or you
otherwise have the right to submit the work.
2. You grant the unfurl bot project a nonexclusive, irrevocable
license to use your submitted contribution in any way.
3. You are capable of granting these rights for the contribution.

By submitting a contribution to the unfurl bot project you agree to
the above statements.

# Contributing Issues

## Prerequisites

* [ ] Have you [searched for duplicates](https://github.com/pmonks/bot-unfurl/issues?utf8=%E2%9C%93&q=)?  A simple search for exception error messages or a summary of the unexpected behaviour should suffice.
* [ ] Are you running the [latest release of the unfurl bot](https://github.com/pmonks/bot-unfurl/commits/master)?

## Raising an Issue
* Create your issue [here](https://github.com/pmonks/bot-unfurl/issues/new).
* New issues contain two templates in the description: bug report and enhancement request. Please pick the most appropriate for your issue, and delete the other.
  * Please also tag the new issue with either "Bug" or "Enhancement".
* Please use [Markdown formatting](https://help.github.com/categories/writing-on-github/)
liberally to assist in readability.
  * [Code fences](https://help.github.com/articles/creating-and-highlighting-code-blocks/) for exception stack traces and log entries, for example, massively improve readability.

# Contributing Pull Requests (Code & Docs)
To make review of PRs easier, please:

 * Please make sure your PRs will merge cleanly - PRs that don't are unlikely to be accepted.
 * For code contributions, follow the general structure of the existing code.
 * For documentation contributions, follow the general structure, language, and tone of the [existing docs](https://github.com/pmonks/bot-unfurl/wiki).
 * Keep PRs small and cohesive - if you have multiple contributions, please submit them as independent PRs.
 * Reference issue #s if your PR has anything to do with an issue (even if it doesn't address it).
 * Minimise "spurious" changes (e.g. whitespace shenanigans).
 * Ensure all new files include a header comment block containing the [Apache License v2.0 and your copyright information](http://www.apache.org/licenses/LICENSE-2.0#apply).
 * If necessary (e.g. due to 3rd party dependency licensing requirements), update the [NOTICE file](https://github.com/pmonks/bot-unfurl/blob/master/NOTICE) with any new attribution notices

## Commit and PR Messages

* **Reference issues, wiki pages, and pull requests liberally!**
* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move button left..." not "Moves button left...")
* Limit the first line to 72 characters or less
* Please start the commit message with one or more applicable emoji:
    * Frequently used:
        * :bug: `:bug:` when fixing a bug
        * :new: `:new:` when implementing an enhancement
        * :ballot_box_with_check: `:ballot_box_with_check:` when completing a task
        * :memo: `:memo:` when writing docs
        * :racehorse: `:racehorse:` when improving performance
        * :art: `:art:` when improving the format/structure of the code
    * Infrequently used:
        * :lock: `:lock:` when dealing with security
        * :fire: `:fire:` when removing code or files
        * :arrow_up: `:arrow_up:` when upgrading dependencies
        * :arrow_down: `:arrow_down:` when downgrading dependencies
        * :penguin: `:penguin:` when fixing something on Linux
        * :apple: `:apple:` when fixing something on Mac OS
        * :checkered_flag: `:checkered_flag:` when fixing something on Windows
        * :white_check_mark: `:white_check_mark:` when adding tests
        * :green_heart: `:green_heart:` when fixing the CI build
    * Unlikely to ever be used in this project (but listed, just in case):
        * :non-potable_water: `:non-potable_water:` when plugging memory leaks
