### What this PR does / why we need it


### Checklist

- [ ] Update changelog in CHANGELOG.md.

### Trigger e2e tests

<!--
We currently have two different pipelines to test both cluster creation and cluster upgrades. You can trigger these pipelines by writing these commands in a pull request comment or description 
- `/test create` : this will trigger the `create-cluster-capi-pure` pipeline.
- `/test upgrade` : this will trigger the `upgrade-cluster-capi-pure` pipeline.

After writing these comments, the pipelines are triggered in [tekton](https://tekton.giantswarm.io/#/pipelineruns). Eventually, the Github checks `create` and `upgrade` for these pipelines should show up in the commit statuses.
It may happen that the status is never shown on Github UI. If you want to check the status or result of the pipelines you can check [tekton](https://tekton.giantswarm.io/#/pipelineruns).

If for some reason you want to skip the e2e tests, remove the following lines.
-->

/test create
/test upgrade
