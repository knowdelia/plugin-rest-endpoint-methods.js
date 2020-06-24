---
name: List repositories accessible to the app installation
example: octokit.apps.listReposAccessibleToInstallation()
route: GET /installation/repositories
scope: apps
type: API method
---

# List repositories accessible to the app installation

List repositories that an app installation can access.

You must use an [installation access token](https://developer.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-an-installation) to access this endpoint.

```js
octokit.apps.listReposAccessibleToInstallation();
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>per_page</td><td>no</td><td>

Results per page (max 100)

</td></tr>
<tr><td>page</td><td>no</td><td>

Page number of the results to fetch.

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/apps/installations/#list-repositories-accessible-to-the-app-installation).