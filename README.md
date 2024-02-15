# Setup dockerode
Setup docker and nodejs

It
- always uses latest available version of LTS

## INSTALLATION
Copy and paste the following snippet into your .yml file.
```
              - name: Setup dockerode
                uses: davidkhala/setup-dockerode@main
            
```

# Known issues
- Support `ubuntu-latest` only (due to ScribeMD/rootless-docker limited suport)
