## Notes

When inside terminal (Cloud9), hugo can be run:

```
hugo serve --bind=0.0.0.0 --port=8080 --baseURL=http://3.239.xxx.xxx/

To get the external IP, run:  curl ipinfo.io

To create new hugo project: 
```

## Creating new hugo site
```
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke themes/ananke
echo "theme = 'ananke'" >> config.toml
hugo server
```