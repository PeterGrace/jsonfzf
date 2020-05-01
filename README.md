# jsonfzf
navigate json tree with jq and fzf
## requires
  - [bash](https://www.gnu.org/software/bash/)
  - [jq](https://github.com/stedolan/jq)
  - [fzf](https://github.com/junegunn/fzf)

## usage
### read existing file
```
jsonfzf path-to-json
```

### read pipeline output
```
kubectl get pods -o json | jsonfzf -
```
