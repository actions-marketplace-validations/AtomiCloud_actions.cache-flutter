# Cache Flutter Packages

Cache Flutter (Pub), Android (Gradle) & iOS (CocoaPods) packages under AtomiCloud

# Get Started

Instruction

```yaml
name: Example Workflow
on: push
jobs:
  Test:
    runs-on: ubuntu-latest
    steps:
      # change this
      - uses: AtomiCloud/actions.cache-flutter@v1
```

<!-- prettier-ignore-start -->
<!-- action-docs-inputs -->
## Inputs

| parameter | description | required | default |
| --- | --- | --- | --- |
| namespacelabs | Using Namespace Lab's runners | `false` | true |
<!-- action-docs-inputs -->

<!-- action-docs-outputs -->

<!-- action-docs-outputs -->

<!-- action-docs-runs -->
## Runs

This action is a `composite` action.
<!-- action-docs-runs -->

<!-- prettier-ignore-end -->
