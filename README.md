# MBlock: simple instance blocklist management for Mastodon

**Requires Mastodon v4.0.0-rc1 or greater**

## Usage

### Prerequisites

1. Generate an access token for `mblock` with admin read and write scopes in `Preferences > Development > New Application`.

### Export

To export your currently blocked instances to an archive:

```
MASTO_DOMAIN=<your.domain> MASTO_TOKEN=<your_token> ./mblock export
```

### Import

To import blocks for instances from an archive, skipping instances that you already have blocked:

```
MASTO_DOMAIN=<your.domain> MASTO_TOKEN=<your_token> ./mblock export
```

_NB: the archive must be called blocked_domains.gz_
