# nginx patches

All patch file's names include the intended nginx version. Three is also
a git tag for each nginx version tested against.

For new versions, please create an issue with the version number or a
pull request with the new file name and updated patch. If the patch
requires no changes we'll just rename and re-tag it.

## `$start_time`

Provides a `$start_time` variable for requests.

```
patch -d /opt/nginx/src/http/ nginx_1.7.10_start_time.diff
```
