## Secrets

URLs and IPs should be entered as GitHub [Repository Secrets](https://github.com/RIT-RC/rc-status-page/settings/secrets/actions). Click "New repository secret" to create a new one.

The GitHub Personal Access Token is also a Repository Secret.

Do not touch the Environment Secrets.

Secrets can be referenced like this: `$<secret_name>`.

## Maintenance Windows

Create an issue and tag it `maintenance`. The issue body needs to have:

```
<!--
start: 2021-02-24T13:00:00.220Z
end: 2021-02-24T14:00:00.220Z
expectedDown: <site_one>, <site_two>, ...
-->
```

Look at issue tags to see options for `expectedDown`.

Issue will automatically close at the `end` timestamp.

[More Details](https://upptime.js.org/docs/scheduled-maintenance)

## 
