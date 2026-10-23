# fork-run-approval-test

Scratch repo: checks whether approving a fork PR's `action_required` run
with a workflow's `GITHUB_TOKEN` starts the run, and whether a downstream
`workflow_run` workflow then fires. To be deleted after the test.

To take part: fork this repo, change `probe.txt`, open a PR.
