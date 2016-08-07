## Heroku Buildpack SSH

A buildpack which configures heroku instances to allow for SSH tunnelling to external resources.

### Usage
To use this buildpack, a configuration file, `ssh.yml`, should be place in your applications `config` directory.

### Configuration
The following is a sample `ssh.yml`.
```yaml
---
known_hosts:
  - github.com
  - # external hosts here
```
