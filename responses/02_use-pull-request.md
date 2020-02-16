## Step 1: Use a pull request for communication

Alternatively you can use a pull request as a "conversation" with the learner. As with the issue based approach you can have more than one step per pull request by having the learning bot responding to the open pull request after the user completes a certain action.

The nice thing about using a pull request is that you can have the learning bot approve it once the user has completed all of the required actions. This works best if you enable branch protection for `master` in `before` step of your courses `config.yml`:

```yaml
before:
  - type: updateBranchProtection
```


### :keyboard: Activity: Respond to my question


1. Review this PR
1. Wait for me to respond
1. Approve the PR
1. Merge the PR
1. Delete the branch


<hr>
<h3 align="center">Return to this pull requests for further comments.</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds. Then refresh the page for your next steps._