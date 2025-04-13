# Setup dockerode

Setup docker and nodejs

- always uses latest available version of LTS

## Usage

```yaml
  - name: Setup dockerode
    uses: davidkhala/setup-dockerode@main
            
```

## Known issues

- Rootless docker is used for `ubuntu-latest` exclusively
