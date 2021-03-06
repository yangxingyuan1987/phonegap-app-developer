# How to Contribute

## Get the Source

    $ git clone https://github.com/phonegap/phonegap-app-developer.git
    $ cd phonegap-app-developer/

## Join the Discussion

We use the [GitHub Issue Tracker][issue-url] for all of our discussions.
You can [filter the discussions][filter-url] with the **discussion** label.

## Submit an Issue

We use the [GitHub Issue Tracker][issue-url] for all of our issues.

## Commits

We expect atomic commits that reference the GitHub issue.

For example:

- `[#33] Fix viewport layout.`
- `[#144] Add PointerEvent support for WP8.`

When no issue is exists, then prefix each commit with the root directory or topic:

- `[doc] Update date in LICENSE.`
- `[www] Fix button style.`
- `[ios] Update icon name in plist.`

## Tags

When a tag affects all platforms, use an ordinary semver tag:

- 0.0.1
- 0.1.0
- 0.1.1
- 0.2.0
- 1.0.0

Platform releases should individually tagged as:

- 1.0.0-android-rc.1
- 1.0.0-android-release
- 1.0.0-ios-release

  [issue-url]: https://github.com/phonegap/phonegap-app-developer/issues
  [filter-url]: https://github.com/phonegap/phonegap-app-developer/issues?labels=discussion&page=1&state=open
