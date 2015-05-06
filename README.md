jira-summary
============

Ruby script to return the Jira issue key and summary in the format:

```
KEY: Summary
```

What it does:

Uses the Jira REST API to lookup the issue summary. Helpful for filling in git commit titles especially in combination with [Text Expander](http://smilesoftware.com/TextExpander/index.html) (or similar tool).

You'll need to copy `jira_sum.yaml.sample` from the git checkout to `~/.jira_sum.yaml`, and then edit is as appropriate.
