# semver-ecr-buildkite-plugin
This plugin provides semantic versioning integration for ECR in Buildkite pipelines.

## Usage Example

Below is an example configuration for using this plugin in a Buildkite pipeline.

```yaml
steps:
  - plugins:
      - amjad-khan/semver-ecr:
          repository: "your-ecr-repo-name"
          region: "region"
          account: "number"
