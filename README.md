# docker-chromium-xvfb-py3

通过Docker镜像提供Selenium，Chromium浏览器，xvfb虚拟化，和Python3环境， 并支持页面中文，否则字体是方块。

Based on [markadams/chromium-xvfb-py3](https://hub.docker.com/r/markadams/chromium-xvfb-py3)

Github [chromium-xvfb-py3](https://github.com/kemixkoo/docker-chromium-xvfb/tree/master/images/python3)


## 版本信息
- Python 3.5
- Chrome=64.0.3282.119
- Driver info: chromedriver=2.36.540471


## 构建

```
docker build -t kemixkoo/chromium-xvfb-py3 .
```

