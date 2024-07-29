# Github Profile Dynamic SVG Statistics
<img align="right" width="200" title="preview" alt="preview" src="https://github.com/zippw/github-profile-dynamic-svg-statistics/blob/main/preview.gif?raw=true"/>

This is my custom solution for displaying various stats on a GitHub profile.

Powered by Yandex Cloud Functions & Managed Service for YDB.<br>
Don't forget to set up the environment variables:
- `ydb_endpoint` (Document API)
- `gh_tkn` ([GitHub personal token](https://github.com/settings/tokens))

> [!TIP]
> If you want to scan your private repositories, enable the "repo" scope when creating the GitHub token.

> [!NOTE]
> The `gh_svg.js` code is intentionally kept compact and without libraries to minimize size and optimize performance in serverless functions (making it faster and more cost-effective).
