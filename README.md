# php_openresty
## about permission
If your php code writes in webroot, run command below before start container:
```bash
chown -R 65534:65534 path-to-mount
```
