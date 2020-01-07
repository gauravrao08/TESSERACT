# TESSERACT
TESSERACT install 
https://medium.com/@jjagadish.in/install-tesseract-3-04-on-centos-7-4573465d8867

https://github.com/EisenVault/install-tesseract-redhat-centos/blob/master/install-tesseract.sh

https://github.com/DanBloomberg/leptonica/releases

```
wget http://www.leptonica.com/source/leptonica-1.73.tar.gz
tar xzvf leptonica-1.73.tar.gz
cd leptonica-1.73
./configure
make
make install
```

https://github.com/tesseract-ocr/tesseract/releases



```
wget https://github.com/tesseract-ocr/tesseract/archive/3.04.01.tar.gz
mv 3.04.01.tar.gz tesseract-3.04.01.tar.gz
tar xzvf tesseract-3.04.01.tar.gz
cd tesseract-3.04.01/
./autogen.sh
./configure

## if getting error then ## export PKG_CONFIG_PATH=/usr/local/lib/pkgconfig/
make
make install
ldconfig
```


