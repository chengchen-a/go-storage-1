# storage

a tool use free CDN store file

## how it works

many website provider api to store image on CDN without authority check, this tool store file pieces as image on CDN. 

## usage

```bash
# upload
storage /path/to/file # upload file to CDN, generated pieces mate for download
# download
storage /path/to/file.meta
```

## supported CDN node 

- ali: alibaba CDN