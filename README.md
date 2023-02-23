# Squad Finder `sf-environments-action`

This action deserialize a dynamic file structure contained in a repository, compresses it and generates a secret.

## :hammer_and_wrench: Usage 

```yaml
- name: Create Secret
  uses: ACE-Lan/sf-environments-action@main
  with:
    action: write
    token: ${{ secrets.MY_TOKEN }}
    org: ACE-Lan
    visibility: all
    environment: production
```

It's worth remembering though that secrets are limited to 64 KB.

## License

See [LICENSE](LICENSE).
