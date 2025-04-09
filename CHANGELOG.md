# CHANGELOG

## v0.8.1 (2025-04-08)

- Correct version string in binary

## v0.8.0 (2025-04-08)

- Logs to `stdout` instead of `stderr` to play nicely with tools like `cronic`
- Bumps minimum version to Go 1.16
- Releases to Homebrew

## v0.7.0

- Fix logrus issue (name case)
- Strucured as Go module
- Add compact logged list of fetched repos
- Friendlier API (usage on no args!)

## v0.6.0

- Add basic authentication

## v0.5.0

- Add `ntag` flag to match "everything but this" tags

## v0.4.0

- Corrected behavior with images that have more than one tag (bug #9)
- Changed the meaning of time-limit (e.g `-day`) in combination with `-latest` flag: it only takes into account whichever means more preserved matching tags

## v0.3.0

- Adapt to new Docker Distribution API

## v0.2.0

- Null pointer bug fix
- Additional features (match by tag/repo, custom latest ignore, debug mode)

## v0.1.0

- First working draft
- Works only with `http`
- Number of repositories can be limited
- Age in years, months, days, or a combination
- Allows dry run
