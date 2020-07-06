# mac-preparation

## Notes

### Search large size files

```sh
sudo du -sh /Users/user_name/Library/* | sort -hr
```

### Delete simulators that are unavailable

```sh
xcrun simctl delete unavailable
```
