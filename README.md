i use [gnu stow](https://www.gnu.org/software/stow/) to manage my scripts. use the below command to make scripts available to use.
```bash
sudo stow -t /usr/local/bin .
```
to remove the scripts:
```bash
sudo stow -D -t /usr/local/bin .
```

these can be placed anywhere as long as they are inside your `$PATH`. \
`mx-` prefix is used to avoid clash with other possible scripts.
