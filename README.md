# semver-ecr-buildkite-plugin
This plugin provides semantic versioning integration for ECR in Buildkite pipelines.

## Usage Example

Below is an example configuration for using this plugin in a Buildkite pipeline.

```yaml
steps:
  - plugins:
      - amjad-khan/semver-ecr#v0.1.0:
          repository: "your-ecr-repo-name"
          region: "region"
          account: "number"
          version_branch: "branch-name"
          initial_version: "v0.0.1"
          tag_suffix: true
