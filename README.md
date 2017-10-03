# mastodon-patches
Patches to the Mastodon source code

## Applying and reversing patches
Download the patch then save it somewhere.
Then, in the mastodon directory (e.g. /srv/mastodon/live):

`git apply /path/to/the_patch_file.patch` will apply a patch, and
`git apply -R /path/to/the_patch_file.patch` will reverse it.
