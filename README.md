# semver-ecr-buildkite-plugin
This plugin provides semantic versioning integration for ECR in Buildkite pipelines.

## Usage Example

Below is an example configuration for using this plugin in a Buildkite pipeline.

```yaml
steps:
  - plugins:
      - demystdata/semver-ecr:
          repository: "your-ecr-repo-name"
          region: "ap-southeast-2"
          account: "number"
