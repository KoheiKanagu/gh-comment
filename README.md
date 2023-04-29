# gh-comment

This GitHub CLI extension is for commenting on multiple pull requests at once.

## Installation

```sh
gh extension install KoheiKanagu/gh-comment
```

## Usage

```sh
% gh comment --help
Usage: gh comment [options]
Options:
  --labels <labels>  Specify labels to filter
  --body <body>      Specify body of comment
  --force            Do not dry run
  -h, --help         Show this help message and exit
```

### Example

If you want to merge all Dependabot PRs, you can use the following command.

```sh
gh comment --labels dependencies --body "@dependabot merge"
```
