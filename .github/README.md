# caddy-lanjelin

This is a **public, but personal** image: built for my own setups, but 
published so others can use it if they find it useful. 
The repository includes a GitHub Actions workflow that automatically tracks new 
upstream Caddy v2 releases and rebuilds this image to keep it up to date.

It is an extended Caddy build with a set of extra modules that I use across my infrastructure.

The module set may change over time as my needs change.

### Included Modules
Current modules compiled into this image:
 - github.com/caddyserver/replace-response

### Published at:

```text
ghcr.io/lanjelin/caddy-lanjelin:<version>
ghcr.io/lanjelin/caddy-lanjelin:latest
```

This image follows the same version tags as upstream Caddy v2 and updates
automatically through GitHub Actions.
