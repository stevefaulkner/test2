on:
 issues:
    types:
      - labeled
      - edited

jobs:
  issue_to_markdown:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
        with:
          token: ${{ secrets.toot }}
      - uses: eunjae-lee/issue-to-markdown@v1
        with:
          token: ${{ secrets.toot }}
      - uses: stefanzweifel/git-auto-commit-action@v4
        with:
          commit_message: 'docs: update contents'
