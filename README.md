## Scrapy

Scrapy is an application framework for crawling web sites and extracting structured data


### Q & A

1. `Could not find a version that satisfies the requirement Twisted>=13.1.0 (from Scrapy) (from versions: )`

```
# https://github.com/scrapy/scrapy/issues/2563
wget https://twistedmatrix.com/Releases/Twisted/17.1/Twisted-17.1.0.tar.bz2

tar -jxvf Twisted-17.1.0.tar.bz2

cd Twisted-17.1.0

python3 setup.py install
```
