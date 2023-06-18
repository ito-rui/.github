## Github Operation Template

### Branch

-   #### [Rules](../docs/Branch-Rules.pdf)

### Issues

-   #### [Rules](../docs/Issues-Rules.pdf)

### Commit

-   #### [Rules](../docs/Commit-Rules.pdf)

#### Syntax

```bash
# If there is a related Issue or Pull request
git commit -m "(Issue or PullRequest): Modifire (*required)" -m "Title (*required)" -m "Text1 (any)" -m "Text2 (any)"

# 関連するIssueやPullRequestがある場合
git commit -m "(Issue or PullRequestの番号): 修飾子（*必須）" -m "タイトル（*必須）" -m "本文1（任意）" -m "本文2（任意）"

# If there is no related Issue or PullRequest
git commit -m "Modifire (*required)" -m "Title (*required)" -m "Text1 (any)" -m "Text2 (any)"

# 関連するIssueやPullRequestがない場合
git commit -m "修飾子（*必須）" -m "タイトル（*必須）" -m "本文1（任意）" -m "本文2（任意）"
```
