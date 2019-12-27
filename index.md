
## Default Variables

### google_chrome_started

Restart app if already running

#### Default value

```yaml
google_chrome_started: true
```

### google_chrome_user

User to run user-specific commands

#### Default value

```yaml
google_chrome_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger
