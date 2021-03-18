# Simple TS Test

This repository is used to test the [actions-merge-release-changes-to-protected-branch](https://github.com/guardian/actions-merge-release-changes-to-protected-branch). As such, it also provides a working example.

## Example

[PR #97](https://github.com/guardian/simple-ts-test/pull/97) shows a small changes which is automatically published to NPM. [PR #98](https://github.com/guardian/simple-ts-test/pull/98) is the automated PR containing the version bump changes which is approved and merged by the action.

## Additional Changes

The `additional-changes` input allows the users to provide configuration denoting extra changes that are expected during the release (e.g. a `CHANGELOG` file). The [additional-changes-example](https://github.com/guardian/simple-ts-test/tree/additional-changes-example) branch shows an example of this configuraiton option in action. [PR #96](https://github.com/guardian/simple-ts-test/pull/96) shows an example PR being automatically approved and merged which contains these additional changes.

test
