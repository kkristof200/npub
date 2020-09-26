# npub

Publish to npm (with version bump (major, min or patch)) and push to github

# Dependencies

[push](https://github.com/kkristof200/push)

[npm_publish_versionbump](https://github.com/kkristof200/npm_publish_versionbump)

# Install (tested on mac)

```bash
# via wget
wget https://raw.githubusercontent.com/kkristof200/npub/master/npub -O /usr/local/bin/npub && chmod u+x /usr/local/bin/npub

# or via curl
curl https://raw.githubusercontent.com/kkristof200/npub/master/npub > /usr/local/bin/npub && chmod u+x /usr/local/bin/npub
```

# Usage

```bash
cd to_desired_new_folder_path

npub
# or
npub 'custom git message'
# or
npub patch|min|minor|maj|major
# or
npub 'custom git message' patch|min|minor|maj|major
# or
npub patch|min|minor|maj|major 'custom git message'
```
