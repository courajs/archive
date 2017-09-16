A repository to archive old repositories. 

Particularly useful for keeping your Github org tidy (or saving you
money if you're on the legacy per-repo billing scheme).

To archive a repo, run `archive.sh <archived_name> <remote_path>`.
All branches are pulled over, prefixed with the repo name. The HEAD
commit is also put in a folder in `master`, for ease of browsing.
`archived_name` will determine the branch prefixes and folder name, and
`remote_path` should be either a filesystem path or remote url suitable
for cloning.

See [`example-archive`](https://github.com/courajs/example-archive) to
see what it looks like populated.

NOTE - please don't use this to archive and delete public repositories.
If you delete public repositories, any links or bookmarks to the repo
will no longer work. Use this to keep your private repos tidy, not to
break the web!

(Only tested on OSX)
