# Rename Site Name

Rename site folder
```console
$ mv sites/site1.local sites/erp.mydomain.com
```

Update nginx configuration 
```console
$ bench setup nginx
```

Reload nginx
```console
$ sudo service nginx reload
```
