# Different tests for MkDocs

This page includes a few different tests for requirements that the Keptn project needs.

## This is a test to include a remote file

```yaml
{% include "https://raw.githubusercontent.com/keptn/lifecycle-toolkit/main/docs/content/en/docs/installation/assets/values-advance-changes.yaml" %}
```

## This is a test to include a local file with a relative path
```yaml
{% include "./install/assets/values-advance-changes.yaml" %}
```

## This is a test to link to a local file

This is link to the [Install Keptn](install/install.md) page.
The great thing is that IntelliJ finds it directly and Ctrl clicking on the file works ❤️.

## This is a test to show invisible pages

This is a [link to a page](invisible.md) that exists but is not linked for the left-side navigation.
