# flask-geoip2
A flask server for a geoip server using MaxMind's brilliant free geoip2 library and database

## Install Maxmind C Extension

https://github.com/maxmind/libmaxminddb

```
brew install libmaxminddb
```

## Download the latest free databases

```
cd data
wget http://geolite.maxmind.com/download/geoip/database/GeoLite2-City.mmdb.gz && gzip -df GeoLite2-City.mmdb.gz 
cd ..
```

## Install the requirements files
```
pip install -r requirements.txt
```

## Run the server!
```
python app.py
```

## Credits
This product includes GeoLite2 data created by MaxMind, available from [http://www.maxmind.com](http://www.maxmind.com)
