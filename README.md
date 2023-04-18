## Notes

Git clone including the git sub-modules:
```
git clone ...
git submodule init
git submodule update

```

When inside terminal (Cloud9), hugo can be run:

```
hugo serve --bind=0.0.0.0 --port=8080 --baseURL=http://3.239.254.242/

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

 dukehugofeb1
this is a Hugo continuous delivery site

![Course1-Hugo-CD](https://user-images.githubusercontent.com/58792/107864165-cd2d2580-6e27-11eb-8607-ed0b7d80c995.jpg)


## Tutorial
You can refer to the book Cloud Computing for Data, [Chapter 02](https://paiml.com/docs/home/books/cloud-computing-for-data/chapter02-cloud-foundations/), to get a full walkthrough of the Hugo Continuous Delivery Setup. 

### Coursera Lab





## Demo Video

Here is a Hugo Website [Continous Deploy from Zero Video](https://www.youtube.com/watch?v=xiodvLdPnvI)
